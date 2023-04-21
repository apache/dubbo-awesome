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
# Warmup Iteration   1: 3.588 ops/ms
# Warmup Iteration   2: 8.484 ops/ms
# Warmup Iteration   3: 10.008 ops/ms
Iteration   1: 10.251 ops/ms
Iteration   2: 10.375 ops/ms
Iteration   3: 10.453 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.360 ±(99.9%) 1.855 ops/ms [Average]
  (min, avg, max) = (10.251, 10.360, 10.453), stdev = 0.102
  CI (99.9%): [8.505, 12.215] (assumes normal distribution)


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
# Warmup Iteration   1: 7.207 ops/ms
# Warmup Iteration   2: 10.533 ops/ms
# Warmup Iteration   3: 11.013 ops/ms
Iteration   1: 10.997 ops/ms
Iteration   2: 11.183 ops/ms
Iteration   3: 11.285 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.155 ±(99.9%) 2.667 ops/ms [Average]
  (min, avg, max) = (10.997, 11.155, 11.285), stdev = 0.146
  CI (99.9%): [8.488, 13.822] (assumes normal distribution)


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
# Warmup Iteration   1: 7.018 ops/ms
# Warmup Iteration   2: 10.027 ops/ms
# Warmup Iteration   3: 10.117 ops/ms
Iteration   1: 10.581 ops/ms
Iteration   2: 10.472 ops/ms
Iteration   3: 10.349 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.467 ±(99.9%) 2.121 ops/ms [Average]
  (min, avg, max) = (10.349, 10.467, 10.581), stdev = 0.116
  CI (99.9%): [8.347, 12.588] (assumes normal distribution)


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
# Warmup Iteration   1: 5.655 ops/ms
# Warmup Iteration   2: 7.500 ops/ms
# Warmup Iteration   3: 7.743 ops/ms
Iteration   1: 7.870 ops/ms
Iteration   2: 8.009 ops/ms
Iteration   3: 7.808 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.895 ±(99.9%) 1.872 ops/ms [Average]
  (min, avg, max) = (7.808, 7.895, 8.009), stdev = 0.103
  CI (99.9%): [6.023, 9.768] (assumes normal distribution)


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
# Warmup Iteration   1: 4.375 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.003 ms/op
Iteration   1: 3.080 ±(99.9%) 0.009 ms/op
Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
Iteration   3: 3.039 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.034 ±(99.9%) 0.886 ms/op [Average]
  (min, avg, max) = (2.983, 3.034, 3.080), stdev = 0.049
  CI (99.9%): [2.147, 3.920] (assumes normal distribution)


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
# Warmup Iteration   1: 4.113 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.003 ms/op
Iteration   1: 2.917 ±(99.9%) 0.001 ms/op
Iteration   2: 2.946 ±(99.9%) 0.003 ms/op
Iteration   3: 2.989 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.951 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (2.917, 2.951, 2.989), stdev = 0.037
  CI (99.9%): [2.283, 3.619] (assumes normal distribution)


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.004 ms/op
Iteration   1: 3.137 ±(99.9%) 0.008 ms/op
Iteration   2: 3.072 ±(99.9%) 0.003 ms/op
Iteration   3: 3.049 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.086 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (3.049, 3.086, 3.137), stdev = 0.045
  CI (99.9%): [2.258, 3.914] (assumes normal distribution)


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
# Warmup Iteration   1: 5.439 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.249 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.042 ms/op
Iteration   1: 4.087 ±(99.9%) 0.010 ms/op
Iteration   2: 4.041 ±(99.9%) 0.025 ms/op
Iteration   3: 4.084 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.071 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (4.041, 4.071, 4.087), stdev = 0.026
  CI (99.9%): [3.603, 4.538] (assumes normal distribution)


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
# Warmup Iteration   1: 4.292 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.115 ms/op
                 createUser·p0.9999: 13.228 ms/op
                 createUser·p1.00:   14.680 ms/op

Iteration   2: 3.104 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  8.174 ms/op
                 createUser·p0.9999: 13.938 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  12.956 ms/op
                 createUser·p0.9999: 19.126 ms/op
                 createUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310278
  mean =      3.093 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 399 
    [ 1.250,  2.500) = 13616 
    [ 2.500,  3.750) = 279370 
    [ 3.750,  5.000) = 15407 
    [ 5.000,  6.250) = 710 
    [ 6.250,  7.500) = 348 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      9.547 ms/op
     p(99.9900) =     18.331 ms/op
     p(99.9990) =     19.389 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.736 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.302 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  7.227 ms/op
                 existUser·p0.9999: 13.071 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.923 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  5.833 ms/op
                 existUser·p0.9999: 21.778 ms/op
                 existUser·p1.00:   22.184 ms/op

Iteration   3: 2.920 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  9.640 ms/op
                 existUser·p0.9999: 18.910 ms/op
                 existUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322455
  mean =      2.977 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31643 
    [ 2.500,  5.000) = 289363 
    [ 5.000,  7.500) = 1105 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.302 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.865 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     22.078 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.749 ms/op
                 getUser·p0.9999: 14.388 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 3.090 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.935 ms/op
                 getUser·p0.9999: 20.555 ms/op
                 getUser·p1.00:   21.037 ms/op

Iteration   3: 3.066 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.901 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.390 ms/op
                 getUser·p0.999:  7.502 ms/op
                 getUser·p0.9999: 25.942 ms/op
                 getUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311904
  mean =      3.079 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10075 
    [ 2.500,  5.000) = 300512 
    [ 5.000,  7.500) = 969 
    [ 7.500, 10.000) = 153 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.709 ms/op
     p(99.9900) =     24.498 ms/op
     p(99.9990) =     26.301 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 5.439 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.172 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.011 ms/op
Iteration   1: 4.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  13.737 ms/op
                 listUser·p0.9999: 17.435 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 4.022 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.337 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.888 ms/op
                 listUser·p0.999:  14.286 ms/op
                 listUser·p0.9999: 20.024 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   3: 4.106 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.024 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.043 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 18.029 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236928
  mean =      4.054 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2219 
    [ 2.500,  5.000) = 209876 
    [ 5.000,  7.500) = 23503 
    [ 7.500, 10.000) = 929 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     18.983 ms/op
     p(99.9990) =     20.357 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.360 ± 1.855  ops/ms
ClientGrpc.existUser                       thrpt       3  11.155 ± 2.667  ops/ms
ClientGrpc.getUser                         thrpt       3  10.467 ± 2.121  ops/ms
ClientGrpc.listUser                        thrpt       3   7.895 ± 1.872  ops/ms
ClientGrpc.createUser                       avgt       3   3.034 ± 0.886   ms/op
ClientGrpc.existUser                        avgt       3   2.951 ± 0.668   ms/op
ClientGrpc.getUser                          avgt       3   3.086 ± 0.828   ms/op
ClientGrpc.listUser                         avgt       3   4.071 ± 0.468   ms/op
ClientGrpc.createUser                     sample  310278   3.093 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.743           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.604           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.547           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.331           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.530           ms/op
ClientGrpc.existUser                      sample  322455   2.977 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.302           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.970           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.865           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.414           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.184           ms/op
ClientGrpc.getUser                        sample  311904   3.079 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.762           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.709           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.498           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.477           ms/op
ClientGrpc.listUser                       sample  236928   4.054 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.024           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.903           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.270           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.983           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.414           ms/op
