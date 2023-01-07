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
# Warmup Iteration   1: 4.905 ops/ms
# Warmup Iteration   2: 9.060 ops/ms
# Warmup Iteration   3: 10.646 ops/ms
Iteration   1: 10.867 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.610 ±(99.9%) 5.736 ops/ms [Average]
  (min, avg, max) = (10.259, 10.610, 10.867), stdev = 0.314
  CI (99.9%): [4.874, 16.345] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.372 ops/ms
# Warmup Iteration   2: 10.889 ops/ms
# Warmup Iteration   3: 11.004 ops/ms
Iteration   1: 10.855 ops/ms
Iteration   2: 11.063 ops/ms
Iteration   3: 10.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.940 ±(99.9%) 1.993 ops/ms [Average]
  (min, avg, max) = (10.855, 10.940, 11.063), stdev = 0.109
  CI (99.9%): [8.947, 12.933] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.613 ops/ms
# Warmup Iteration   2: 9.992 ops/ms
# Warmup Iteration   3: 10.471 ops/ms
Iteration   1: 10.680 ops/ms
Iteration   2: 10.738 ops/ms
Iteration   3: 10.616 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.678 ±(99.9%) 1.117 ops/ms [Average]
  (min, avg, max) = (10.616, 10.678, 10.738), stdev = 0.061
  CI (99.9%): [9.561, 11.795] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.080 ops/ms
# Warmup Iteration   2: 8.031 ops/ms
# Warmup Iteration   3: 8.083 ops/ms
Iteration   1: 8.153 ops/ms
Iteration   2: 8.316 ops/ms
Iteration   3: 8.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.174 ±(99.9%) 2.407 ops/ms [Average]
  (min, avg, max) = (8.054, 8.174, 8.316), stdev = 0.132
  CI (99.9%): [5.767, 10.582] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.089 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.002 ms/op
Iteration   1: 3.056 ±(99.9%) 0.010 ms/op
Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
Iteration   3: 3.119 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.111 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.056, 3.111, 3.157), stdev = 0.051
  CI (99.9%): [2.175, 4.046] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.611 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.003 ms/op
Iteration   2: 2.948 ±(99.9%) 0.005 ms/op
Iteration   3: 2.960 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.957 ±(99.9%) 0.133 ms/op [Average]
  (min, avg, max) = (2.948, 2.957, 2.961), stdev = 0.007
  CI (99.9%): [2.824, 3.089] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.840 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.141 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.002 ms/op
Iteration   1: 3.009 ±(99.9%) 0.002 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.034 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (3.009, 3.034, 3.055), stdev = 0.023
  CI (99.9%): [2.608, 3.460] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.965 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.955 ±(99.9%) 0.019 ms/op
Iteration   1: 3.940 ±(99.9%) 0.011 ms/op
Iteration   2: 3.984 ±(99.9%) 0.032 ms/op
Iteration   3: 3.911 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.945 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.911, 3.945, 3.984), stdev = 0.037
  CI (99.9%): [3.279, 4.612] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.007 ms/op
Iteration   1: 3.059 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  6.443 ms/op
                 createUser·p0.9999: 18.156 ms/op
                 createUser·p1.00:   18.579 ms/op

Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.459 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  8.215 ms/op
                 createUser·p0.9999: 12.370 ms/op
                 createUser·p1.00:   12.943 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.545 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.312 ms/op
                 createUser·p0.999:  11.095 ms/op
                 createUser·p0.9999: 17.400 ms/op
                 createUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313915
  mean =      3.055 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25980 
    [ 2.500,  5.000) = 286953 
    [ 5.000,  7.500) = 650 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.940 ms/op
     p(99.9900) =     17.616 ms/op
     p(99.9990) =     18.575 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.615 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.971 ±(99.9%) 0.006 ms/op
Iteration   1: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.348 ms/op
                 existUser·p0.9999: 15.571 ms/op
                 existUser·p1.00:   16.695 ms/op

Iteration   2: 2.877 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.424 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.802 ms/op
                 existUser·p0.9999: 17.850 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 2.906 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.641 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  10.665 ms/op
                 existUser·p0.9999: 24.543 ms/op
                 existUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330391
  mean =      2.905 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53402 
    [ 2.500,  5.000) = 275925 
    [ 5.000,  7.500) = 677 
    [ 7.500, 10.000) = 159 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.645 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      8.094 ms/op
     p(99.9900) =     18.316 ms/op
     p(99.9990) =     24.917 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.453 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  6.409 ms/op
                 getUser·p0.9999: 16.506 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 3.163 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.865 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.075 ms/op
                 getUser·p0.9999: 13.311 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.373 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.638 ms/op
                 getUser·p0.9999: 13.733 ms/op
                 getUser·p1.00:   13.976 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312874
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2622 
    [ 1.250,  2.500) = 24428 
    [ 2.500,  3.750) = 257785 
    [ 3.750,  5.000) = 27051 
    [ 5.000,  6.250) = 600 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 46 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.579 ms/op
     p(99.9900) =     15.562 ms/op
     p(99.9990) =     16.834 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.089 ±(99.9%) 0.012 ms/op
Iteration   1: 3.966 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.030 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.059 ms/op
                 listUser·p0.9999: 14.253 ms/op
                 listUser·p1.00:   15.401 ms/op

Iteration   2: 3.907 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.522 ms/op
                 listUser·p0.9999: 17.132 ms/op
                 listUser·p1.00:   17.498 ms/op

Iteration   3: 3.847 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.840 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  16.797 ms/op
                 listUser·p0.9999: 20.929 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245607
  mean =      3.906 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5562 
    [ 2.500,  5.000) = 215827 
    [ 5.000,  7.500) = 23161 
    [ 7.500, 10.000) = 608 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     13.582 ms/op
     p(99.9900) =     20.199 ms/op
     p(99.9990) =     21.400 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.610 ± 5.736  ops/ms
ClientGrpc.existUser                       thrpt       3  10.940 ± 1.993  ops/ms
ClientGrpc.getUser                         thrpt       3  10.678 ± 1.117  ops/ms
ClientGrpc.listUser                        thrpt       3   8.174 ± 2.407  ops/ms
ClientGrpc.createUser                       avgt       3   3.111 ± 0.936   ms/op
ClientGrpc.existUser                        avgt       3   2.957 ± 0.133   ms/op
ClientGrpc.getUser                          avgt       3   3.034 ± 0.426   ms/op
ClientGrpc.listUser                         avgt       3   3.945 ± 0.666   ms/op
ClientGrpc.createUser                     sample  313915   3.055 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.459           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.940           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.616           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.791           ms/op
ClientGrpc.existUser                      sample  330391   2.905 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.607           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.316           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.002           ms/op
ClientGrpc.getUser                        sample  312874   3.068 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.373           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.579           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.562           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.908           ms/op
ClientGrpc.listUser                       sample  245607   3.906 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.840           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.760           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.669           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.582           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.199           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.758           ms/op
