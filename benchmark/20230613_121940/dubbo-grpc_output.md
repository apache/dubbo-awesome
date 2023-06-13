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
# Warmup Iteration   1: 4.372 ops/ms
# Warmup Iteration   2: 9.446 ops/ms
# Warmup Iteration   3: 10.413 ops/ms
Iteration   1: 10.490 ops/ms
Iteration   2: 10.675 ops/ms
Iteration   3: 10.621 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.595 ±(99.9%) 1.736 ops/ms [Average]
  (min, avg, max) = (10.490, 10.595, 10.675), stdev = 0.095
  CI (99.9%): [8.859, 12.331] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.943 ops/ms
# Warmup Iteration   2: 10.673 ops/ms
# Warmup Iteration   3: 11.150 ops/ms
Iteration   1: 10.984 ops/ms
Iteration   2: 11.134 ops/ms
Iteration   3: 11.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.133 ±(99.9%) 2.710 ops/ms [Average]
  (min, avg, max) = (10.984, 11.133, 11.281), stdev = 0.149
  CI (99.9%): [8.423, 13.843] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.368 ops/ms
# Warmup Iteration   2: 10.103 ops/ms
# Warmup Iteration   3: 10.373 ops/ms
Iteration   1: 10.582 ops/ms
Iteration   2: 10.481 ops/ms
Iteration   3: 10.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.597 ±(99.9%) 2.286 ops/ms [Average]
  (min, avg, max) = (10.481, 10.597, 10.730), stdev = 0.125
  CI (99.9%): [8.311, 12.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.611 ops/ms
# Warmup Iteration   2: 7.663 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 8.115 ops/ms
Iteration   2: 8.183 ops/ms
Iteration   3: 8.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.101 ±(99.9%) 1.633 ops/ms [Average]
  (min, avg, max) = (8.006, 8.101, 8.183), stdev = 0.090
  CI (99.9%): [6.468, 9.735] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.188 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.003 ms/op
Iteration   1: 3.011 ±(99.9%) 0.002 ms/op
Iteration   2: 3.071 ±(99.9%) 0.002 ms/op
Iteration   3: 3.085 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.056 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.011, 3.056, 3.085), stdev = 0.039
  CI (99.9%): [2.343, 3.769] (assumes normal distribution)


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.954 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.913 ±(99.9%) 0.002 ms/op
Iteration   1: 2.937 ±(99.9%) 0.003 ms/op
Iteration   2: 2.897 ±(99.9%) 0.003 ms/op
Iteration   3: 2.909 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (2.897, 2.914, 2.937), stdev = 0.021
  CI (99.9%): [2.536, 3.293] (assumes normal distribution)


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.003 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 3.058 ±(99.9%) 0.004 ms/op
Iteration   3: 3.008 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.019 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (2.991, 3.019, 3.058), stdev = 0.035
  CI (99.9%): [2.382, 3.656] (assumes normal distribution)


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
# Warmup Iteration   1: 5.049 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.018 ms/op
Iteration   1: 3.938 ±(99.9%) 0.013 ms/op
Iteration   2: 3.937 ±(99.9%) 0.019 ms/op
Iteration   3: 3.942 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.939 ±(99.9%) 0.044 ms/op [Average]
  (min, avg, max) = (3.937, 3.939, 3.942), stdev = 0.002
  CI (99.9%): [3.895, 3.984] (assumes normal distribution)


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.005 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.143 ms/op
                 createUser·p0.9999: 12.508 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   2: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  6.791 ms/op
                 createUser·p0.9999: 13.930 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  13.230 ms/op
                 createUser·p0.9999: 16.596 ms/op
                 createUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313621
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 511 
    [ 1.250,  2.500) = 23497 
    [ 2.500,  3.750) = 271655 
    [ 3.750,  5.000) = 16610 
    [ 5.000,  6.250) = 649 
    [ 6.250,  7.500) = 182 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.373 ms/op
     p(99.9000) =      9.568 ms/op
     p(99.9900) =     16.082 ms/op
     p(99.9990) =     16.932 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 3.792 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.006 ms/op
Iteration   1: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.050 ms/op
                 existUser·p0.9999: 15.563 ms/op
                 existUser·p1.00:   16.155 ms/op

Iteration   2: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.424 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  5.272 ms/op
                 existUser·p0.9999: 14.352 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.431 ms/op
                 existUser·p0.9999: 17.995 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329151
  mean =      2.914 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1593 
    [ 1.250,  2.500) = 35105 
    [ 2.500,  3.750) = 283263 
    [ 3.750,  5.000) = 8462 
    [ 5.000,  6.250) = 360 
    [ 6.250,  7.500) = 159 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.424 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =      6.438 ms/op
     p(99.9900) =     16.549 ms/op
     p(99.9990) =     18.223 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.348 ms/op
                 getUser·p0.9999: 12.503 ms/op
                 getUser·p1.00:   12.648 ms/op

Iteration   2: 3.027 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.374 ms/op
                 getUser·p0.999:  7.482 ms/op
                 getUser·p0.9999: 22.034 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  9.272 ms/op
                 getUser·p0.9999: 23.197 ms/op
                 getUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315216
  mean =      3.045 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18599 
    [ 2.500,  5.000) = 295349 
    [ 5.000,  7.500) = 938 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.757 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.774 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 5.123 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.299 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.011 ms/op
Iteration   1: 4.020 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.764 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  13.943 ms/op
                 listUser·p0.9999: 24.053 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   2: 3.987 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.014 ms/op
                 listUser·p0.9999: 17.529 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 4.060 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.960 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  20.156 ms/op
                 listUser·p0.9999: 27.922 ms/op
                 listUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238742
  mean =      4.022 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3343 
    [ 2.500,  5.000) = 210742 
    [ 5.000,  7.500) = 23213 
    [ 7.500, 10.000) = 1026 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     15.110 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     29.984 ms/op
     p(99.9999) =     30.507 ms/op
    p(100.0000) =     30.507 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.595 ± 1.736  ops/ms
ClientGrpc.existUser                       thrpt       3  11.133 ± 2.710  ops/ms
ClientGrpc.getUser                         thrpt       3  10.597 ± 2.286  ops/ms
ClientGrpc.listUser                        thrpt       3   8.101 ± 1.633  ops/ms
ClientGrpc.createUser                       avgt       3   3.056 ± 0.713   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 0.379   ms/op
ClientGrpc.getUser                          avgt       3   3.019 ± 0.637   ms/op
ClientGrpc.listUser                         avgt       3   3.939 ± 0.044   ms/op
ClientGrpc.createUser                     sample  313621   3.063 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.711           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.373           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.568           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.082           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.072           ms/op
ClientGrpc.existUser                      sample  329151   2.914 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.424           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.438           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.549           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.416           ms/op
ClientGrpc.getUser                        sample  315216   3.045 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.713           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.757           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.774           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.053           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.626           ms/op
ClientGrpc.listUser                       sample  238742   4.022 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.764           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.070           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.110           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.853           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.507           ms/op
