# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.118 ops/ms
# Warmup Iteration   2: 6.880 ops/ms
# Warmup Iteration   3: 7.848 ops/ms
Iteration   1: 8.432 ops/ms
Iteration   2: 7.827 ops/ms
Iteration   3: 8.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.161 ±(99.9%) 5.607 ops/ms [Average]
  (min, avg, max) = (7.827, 8.161, 8.432), stdev = 0.307
  CI (99.9%): [2.555, 13.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.991 ops/ms
# Warmup Iteration   2: 8.154 ops/ms
# Warmup Iteration   3: 8.419 ops/ms
Iteration   1: 8.445 ops/ms
Iteration   2: 8.306 ops/ms
Iteration   3: 8.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.426 ±(99.9%) 2.056 ops/ms [Average]
  (min, avg, max) = (8.306, 8.426, 8.529), stdev = 0.113
  CI (99.9%): [6.371, 10.482] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.296 ops/ms
# Warmup Iteration   2: 8.036 ops/ms
# Warmup Iteration   3: 7.895 ops/ms
Iteration   1: 7.997 ops/ms
Iteration   2: 8.107 ops/ms
Iteration   3: 8.797 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.300 ±(99.9%) 7.907 ops/ms [Average]
  (min, avg, max) = (7.997, 8.300, 8.797), stdev = 0.433
  CI (99.9%): [0.393, 16.207] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.034 ops/ms
# Warmup Iteration   2: 6.218 ops/ms
# Warmup Iteration   3: 6.363 ops/ms
Iteration   1: 6.226 ops/ms
Iteration   2: 6.382 ops/ms
Iteration   3: 6.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.399 ±(99.9%) 3.334 ops/ms [Average]
  (min, avg, max) = (6.226, 6.399, 6.590), stdev = 0.183
  CI (99.9%): [3.065, 9.733] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.629 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.004 ms/op
Iteration   1: 3.787 ±(99.9%) 0.003 ms/op
Iteration   2: 3.868 ±(99.9%) 0.004 ms/op
Iteration   3: 3.793 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.816 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.787, 3.816, 3.868), stdev = 0.045
  CI (99.9%): [2.995, 4.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.150 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.008 ms/op
Iteration   1: 3.805 ±(99.9%) 0.003 ms/op
Iteration   2: 3.578 ±(99.9%) 0.003 ms/op
Iteration   3: 3.695 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.693 ±(99.9%) 2.073 ms/op [Average]
  (min, avg, max) = (3.578, 3.693, 3.805), stdev = 0.114
  CI (99.9%): [1.619, 5.766] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.534 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.821 ±(99.9%) 0.004 ms/op
Iteration   1: 3.707 ±(99.9%) 0.004 ms/op
Iteration   2: 3.866 ±(99.9%) 0.003 ms/op
Iteration   3: 3.954 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.842 ±(99.9%) 2.291 ms/op [Average]
  (min, avg, max) = (3.707, 3.842, 3.954), stdev = 0.126
  CI (99.9%): [1.551, 6.133] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.516 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.195 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.990 ±(99.9%) 0.009 ms/op
Iteration   1: 5.085 ±(99.9%) 0.022 ms/op
Iteration   2: 4.897 ±(99.9%) 0.009 ms/op
Iteration   3: 4.992 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.991 ±(99.9%) 1.710 ms/op [Average]
  (min, avg, max) = (4.897, 4.991, 5.085), stdev = 0.094
  CI (99.9%): [3.282, 6.701] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.694 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.263 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.012 ms/op
Iteration   1: 4.168 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.292 ms/op
                 createUser·p0.50:   4.030 ms/op
                 createUser·p0.90:   5.194 ms/op
                 createUser·p0.95:   5.816 ms/op
                 createUser·p0.99:   8.110 ms/op
                 createUser·p0.999:  13.264 ms/op
                 createUser·p0.9999: 17.334 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   2: 4.090 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.998 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.640 ms/op
                 createUser·p0.99:   8.301 ms/op
                 createUser·p0.999:  14.858 ms/op
                 createUser·p0.9999: 17.760 ms/op
                 createUser·p1.00:   19.137 ms/op

Iteration   3: 4.180 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.525 ms/op
                 createUser·p0.50:   4.018 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.997 ms/op
                 createUser·p0.99:   8.471 ms/op
                 createUser·p0.999:  16.941 ms/op
                 createUser·p0.9999: 23.222 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 231514
  mean =      4.146 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8015 
    [ 2.500,  5.000) = 193480 
    [ 5.000,  7.500) = 26517 
    [ 7.500, 10.000) = 2634 
    [10.000, 12.500) = 517 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     14.491 ms/op
     p(99.9900) =     21.232 ms/op
     p(99.9990) =     23.628 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.205 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.975 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.011 ms/op
Iteration   1: 3.681 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   3.604 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.776 ms/op
                 existUser·p0.99:   6.742 ms/op
                 existUser·p0.999:  10.799 ms/op
                 existUser·p0.9999: 16.683 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   2: 3.716 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   5.902 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 16.548 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   3: 3.849 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  14.336 ms/op
                 existUser·p0.9999: 18.907 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 255954
  mean =      3.747 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 172 
    [ 1.250,  2.500) = 7636 
    [ 2.500,  3.750) = 135020 
    [ 3.750,  5.000) = 102028 
    [ 5.000,  6.250) = 8200 
    [ 6.250,  7.500) = 1476 
    [ 7.500,  8.750) = 542 
    [ 8.750, 10.000) = 366 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 101 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     12.059 ms/op
     p(99.9900) =     18.167 ms/op
     p(99.9990) =     19.311 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.519 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.012 ms/op
Iteration   1: 4.137 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   5.136 ms/op
                 getUser·p0.95:   5.890 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  14.565 ms/op
                 getUser·p0.9999: 20.555 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   2: 3.965 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  12.309 ms/op
                 getUser·p0.9999: 22.348 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   3: 3.841 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   7.414 ms/op
                 getUser·p0.999:  12.059 ms/op
                 getUser·p0.9999: 25.571 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 241235
  mean =      3.977 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10145 
    [ 2.500,  5.000) = 210029 
    [ 5.000,  7.500) = 18296 
    [ 7.500, 10.000) = 1964 
    [10.000, 12.500) = 526 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.423 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     24.736 ms/op
     p(99.9990) =     27.195 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.320 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.164 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.150 ±(99.9%) 0.018 ms/op
Iteration   1: 4.881 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.144 ms/op
                 listUser·p0.95:   7.225 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  16.697 ms/op
                 listUser·p0.9999: 23.505 ms/op
                 listUser·p1.00:   25.526 ms/op

Iteration   2: 4.911 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.160 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 22.231 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   3: 4.899 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.398 ms/op
                 listUser·p0.95:   7.053 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  18.895 ms/op
                 listUser·p0.9999: 22.345 ms/op
                 listUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196100
  mean =      4.897 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 312 
    [ 2.500,  5.000) = 134772 
    [ 5.000,  7.500) = 54054 
    [ 7.500, 10.000) = 6089 
    [10.000, 12.500) = 433 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.300 ms/op
     p(95.0000) =      7.143 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     22.655 ms/op
     p(99.9990) =     25.544 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.161 ± 5.607  ops/ms
ClientGrpc.existUser                       thrpt       3   8.426 ± 2.056  ops/ms
ClientGrpc.getUser                         thrpt       3   8.300 ± 7.907  ops/ms
ClientGrpc.listUser                        thrpt       3   6.399 ± 3.334  ops/ms
ClientGrpc.createUser                       avgt       3   3.816 ± 0.821   ms/op
ClientGrpc.existUser                        avgt       3   3.693 ± 2.073   ms/op
ClientGrpc.getUser                          avgt       3   3.842 ± 2.291   ms/op
ClientGrpc.listUser                         avgt       3   4.991 ± 1.710   ms/op
ClientGrpc.createUser                     sample  231514   4.146 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.525           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.194           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.833           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.290           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.491           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.232           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  255954   3.747 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.771           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.423           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.059           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.167           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.431           ms/op
ClientGrpc.getUser                        sample  241235   3.977 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.783           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.915           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.423           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.758           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.173           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.736           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.394           ms/op
ClientGrpc.listUser                       sample  196100   4.897 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.374           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.143           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.733           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.170           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.655           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.985           ms/op
