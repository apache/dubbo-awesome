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
# Warmup Iteration   1: 3.917 ops/ms
# Warmup Iteration   2: 8.403 ops/ms
# Warmup Iteration   3: 9.799 ops/ms
Iteration   1: 10.407 ops/ms
Iteration   2: 10.294 ops/ms
Iteration   3: 10.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.336 ±(99.9%) 1.120 ops/ms [Average]
  (min, avg, max) = (10.294, 10.336, 10.407), stdev = 0.061
  CI (99.9%): [9.217, 11.456] (assumes normal distribution)


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
# Warmup Iteration   1: 7.168 ops/ms
# Warmup Iteration   2: 10.399 ops/ms
# Warmup Iteration   3: 10.747 ops/ms
Iteration   1: 11.031 ops/ms
Iteration   2: 10.799 ops/ms
Iteration   3: 10.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.928 ±(99.9%) 2.158 ops/ms [Average]
  (min, avg, max) = (10.799, 10.928, 11.031), stdev = 0.118
  CI (99.9%): [8.771, 13.086] (assumes normal distribution)


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
# Warmup Iteration   1: 6.723 ops/ms
# Warmup Iteration   2: 9.867 ops/ms
# Warmup Iteration   3: 10.395 ops/ms
Iteration   1: 10.403 ops/ms
Iteration   2: 10.663 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.511 ±(99.9%) 2.469 ops/ms [Average]
  (min, avg, max) = (10.403, 10.511, 10.663), stdev = 0.135
  CI (99.9%): [8.042, 12.979] (assumes normal distribution)


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
# Warmup Iteration   1: 5.335 ops/ms
# Warmup Iteration   2: 7.986 ops/ms
# Warmup Iteration   3: 8.166 ops/ms
Iteration   1: 8.106 ops/ms
Iteration   2: 8.102 ops/ms
Iteration   3: 8.181 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.130 ±(99.9%) 0.817 ops/ms [Average]
  (min, avg, max) = (8.102, 8.130, 8.181), stdev = 0.045
  CI (99.9%): [7.313, 8.947] (assumes normal distribution)


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.003 ms/op
Iteration   1: 3.047 ±(99.9%) 0.004 ms/op
Iteration   2: 3.049 ±(99.9%) 0.003 ms/op
Iteration   3: 3.050 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.048 ±(99.9%) 0.034 ms/op [Average]
  (min, avg, max) = (3.047, 3.048, 3.050), stdev = 0.002
  CI (99.9%): [3.015, 3.082] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.968 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.002 ms/op
Iteration   1: 2.886 ±(99.9%) 0.002 ms/op
Iteration   2: 2.899 ±(99.9%) 0.002 ms/op
Iteration   3: 2.874 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.886 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.874, 2.886, 2.899), stdev = 0.013
  CI (99.9%): [2.655, 3.117] (assumes normal distribution)


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
# Warmup Iteration   1: 4.207 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.003 ms/op
Iteration   1: 3.083 ±(99.9%) 0.003 ms/op
Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
Iteration   3: 3.019 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 0.679 ms/op [Average]
  (min, avg, max) = (3.019, 3.062, 3.084), stdev = 0.037
  CI (99.9%): [2.383, 3.742] (assumes normal distribution)


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
# Warmup Iteration   1: 4.922 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.191 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.017 ms/op
Iteration   1: 3.897 ±(99.9%) 0.009 ms/op
Iteration   2: 4.015 ±(99.9%) 0.011 ms/op
Iteration   3: 3.862 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.924 ±(99.9%) 1.470 ms/op [Average]
  (min, avg, max) = (3.862, 3.924, 4.015), stdev = 0.081
  CI (99.9%): [2.454, 5.394] (assumes normal distribution)


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
# Warmup Iteration   1: 4.127 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.733 ms/op
                 createUser·p0.9999: 17.707 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.494 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.843 ms/op
                 createUser·p0.9999: 17.640 ms/op
                 createUser·p1.00:   19.399 ms/op

Iteration   3: 3.007 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.895 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 26.935 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319297
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24899 
    [ 2.500,  5.000) = 292876 
    [ 5.000,  7.500) = 1114 
    [ 7.500, 10.000) = 164 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.151 ms/op
     p(99.9900) =     25.922 ms/op
     p(99.9990) =     27.191 ms/op
     p(99.9999) =     27.886 ms/op
    p(100.0000) =     27.886 ms/op


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.005 ms/op
Iteration   1: 2.919 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  7.812 ms/op
                 existUser·p0.9999: 16.548 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   2: 2.942 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  7.784 ms/op
                 existUser·p0.9999: 14.242 ms/op
                 existUser·p1.00:   14.533 ms/op

Iteration   3: 2.881 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  8.151 ms/op
                 existUser·p0.9999: 16.481 ms/op
                 existUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329360
  mean =      2.914 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1143 
    [ 1.250,  2.500) = 39026 
    [ 2.500,  3.750) = 280441 
    [ 3.750,  5.000) = 7567 
    [ 5.000,  6.250) = 592 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.823 ms/op
     p(99.9900) =     16.418 ms/op
     p(99.9990) =     16.847 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 4.380 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.202 ms/op
                 getUser·p0.9999: 18.645 ms/op
                 getUser·p1.00:   18.874 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.343 ms/op
                 getUser·p0.999:  6.212 ms/op
                 getUser·p0.9999: 25.404 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 2.987 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.840 ms/op
                 getUser·p0.9999: 21.375 ms/op
                 getUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319678
  mean =      3.003 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22713 
    [ 2.500,  5.000) = 295564 
    [ 5.000,  7.500) = 1042 
    [ 7.500, 10.000) = 167 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.725 ms/op
     p(99.9900) =     24.513 ms/op
     p(99.9990) =     25.618 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


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
# Warmup Iteration   1: 5.112 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.012 ms/op
Iteration   1: 4.030 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.024 ms/op
                 listUser·p0.999:  13.648 ms/op
                 listUser·p0.9999: 16.257 ms/op
                 listUser·p1.00:   16.515 ms/op

Iteration   2: 3.943 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.044 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  16.151 ms/op
                 listUser·p0.9999: 25.581 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   3: 4.042 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  19.096 ms/op
                 listUser·p0.9999: 28.317 ms/op
                 listUser·p1.00:   28.738 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239566
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3214 
    [ 2.500,  5.000) = 211411 
    [ 5.000,  7.500) = 23533 
    [ 7.500, 10.000) = 964 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.825 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     15.719 ms/op
     p(99.9900) =     26.316 ms/op
     p(99.9990) =     28.725 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.336 ± 1.120  ops/ms
ClientGrpc.existUser                       thrpt       3  10.928 ± 2.158  ops/ms
ClientGrpc.getUser                         thrpt       3  10.511 ± 2.469  ops/ms
ClientGrpc.listUser                        thrpt       3   8.130 ± 0.817  ops/ms
ClientGrpc.createUser                       avgt       3   3.048 ± 0.034   ms/op
ClientGrpc.existUser                        avgt       3   2.886 ± 0.231   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 0.679   ms/op
ClientGrpc.listUser                         avgt       3   3.924 ± 1.470   ms/op
ClientGrpc.createUser                     sample  319297   3.006 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.627           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.469           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.151           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.922           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.886           ms/op
ClientGrpc.existUser                      sample  329360   2.914 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.715           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.823           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.418           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.941           ms/op
ClientGrpc.getUser                        sample  319678   3.003 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.725           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.513           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.690           ms/op
ClientGrpc.listUser                       sample  239566   4.004 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.992           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.719           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.316           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.738           ms/op
