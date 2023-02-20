# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ops/ms
# Warmup Iteration   2: 8.758 ops/ms
# Warmup Iteration   3: 9.798 ops/ms
Iteration   1: 9.867 ops/ms
Iteration   2: 9.859 ops/ms
Iteration   3: 9.801 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.842 ±(99.9%) 0.654 ops/ms [Average]
  (min, avg, max) = (9.801, 9.842, 9.867), stdev = 0.036
  CI (99.9%): [9.188, 10.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.024 ops/ms
# Warmup Iteration   2: 10.204 ops/ms
# Warmup Iteration   3: 10.755 ops/ms
Iteration   1: 10.629 ops/ms
Iteration   2: 10.638 ops/ms
Iteration   3: 10.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.647 ±(99.9%) 0.443 ops/ms [Average]
  (min, avg, max) = (10.629, 10.647, 10.675), stdev = 0.024
  CI (99.9%): [10.205, 11.090] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.503 ops/ms
# Warmup Iteration   2: 9.988 ops/ms
# Warmup Iteration   3: 10.131 ops/ms
Iteration   1: 10.081 ops/ms
Iteration   2: 10.084 ops/ms
Iteration   3: 10.115 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.093 ±(99.9%) 0.345 ops/ms [Average]
  (min, avg, max) = (10.081, 10.093, 10.115), stdev = 0.019
  CI (99.9%): [9.748, 10.438] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.238 ops/ms
# Warmup Iteration   2: 7.582 ops/ms
# Warmup Iteration   3: 7.648 ops/ms
Iteration   1: 7.841 ops/ms
Iteration   2: 7.861 ops/ms
Iteration   3: 7.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.881 ±(99.9%) 0.976 ops/ms [Average]
  (min, avg, max) = (7.841, 7.881, 7.942), stdev = 0.053
  CI (99.9%): [6.906, 8.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.009 ms/op
Iteration   1: 3.199 ±(99.9%) 0.002 ms/op
Iteration   2: 3.287 ±(99.9%) 0.002 ms/op
Iteration   3: 3.162 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.216 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (3.162, 3.216, 3.287), stdev = 0.064
  CI (99.9%): [2.049, 4.382] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.963 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.002 ms/op
Iteration   1: 3.102 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.058 ±(99.9%) 0.853 ms/op [Average]
  (min, avg, max) = (3.008, 3.058, 3.102), stdev = 0.047
  CI (99.9%): [2.205, 3.910] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.445 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.003 ms/op
Iteration   1: 3.145 ±(99.9%) 0.003 ms/op
Iteration   2: 3.174 ±(99.9%) 0.002 ms/op
Iteration   3: 3.111 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.143 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (3.111, 3.143, 3.174), stdev = 0.032
  CI (99.9%): [2.567, 3.719] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.350 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.024 ms/op
Iteration   1: 3.996 ±(99.9%) 0.009 ms/op
Iteration   2: 4.022 ±(99.9%) 0.008 ms/op
Iteration   3: 4.075 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.031 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (3.996, 4.031, 4.075), stdev = 0.040
  CI (99.9%): [3.295, 4.767] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.502 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.346 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.009 ms/op
Iteration   1: 3.180 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.447 ms/op
                 createUser·p0.9999: 23.787 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.173 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.743 ms/op
                 createUser·p0.9999: 25.228 ms/op
                 createUser·p1.00:   26.083 ms/op

Iteration   3: 3.033 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  12.871 ms/op
                 createUser·p0.9999: 27.422 ms/op
                 createUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307269
  mean =      3.127 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31997 
    [ 2.500,  5.000) = 274103 
    [ 5.000,  7.500) = 760 
    [ 7.500, 10.000) = 163 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.813 ms/op
     p(95.0000) =      4.028 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.174 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     27.623 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.275 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.007 ms/op
Iteration   1: 3.067 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.533 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 21.449 ms/op
                 existUser·p1.00:   21.791 ms/op

Iteration   2: 3.017 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.994 ms/op
                 existUser·p0.9999: 33.554 ms/op
                 existUser·p1.00:   33.817 ms/op

Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   3.981 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.083 ms/op
                 existUser·p0.9999: 25.405 ms/op
                 existUser·p1.00:   25.854 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312606
  mean =      3.069 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38360 
    [ 2.500,  5.000) = 272916 
    [ 5.000,  7.500) = 897 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.249 ms/op
     p(99.9900) =     31.751 ms/op
     p(99.9990) =     33.686 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.571 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.301 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.007 ms/op
Iteration   1: 3.210 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.932 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  8.260 ms/op
                 getUser·p0.9999: 14.551 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   2: 3.157 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.501 ms/op
                 getUser·p0.999:  7.316 ms/op
                 getUser·p0.9999: 15.876 ms/op
                 getUser·p1.00:   16.302 ms/op

Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.881 ms/op
                 getUser·p0.9999: 18.527 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304105
  mean =      3.157 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19252 
    [ 2.500,  5.000) = 283381 
    [ 5.000,  7.500) = 1074 
    [ 7.500, 10.000) = 221 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.895 ms/op
     p(99.9900) =     17.668 ms/op
     p(99.9990) =     19.691 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.566 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.013 ms/op
Iteration   1: 4.108 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.028 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 19.667 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 4.167 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  15.597 ms/op
                 listUser·p0.9999: 18.099 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.159 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.169 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 22.260 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231678
  mean =      4.144 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1443 
    [ 2.500,  5.000) = 198928 
    [ 5.000,  7.500) = 29502 
    [ 7.500, 10.000) = 1342 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     16.291 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     22.460 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.842 ± 0.654  ops/ms
ClientGrpc.existUser                       thrpt       3  10.647 ± 0.443  ops/ms
ClientGrpc.getUser                         thrpt       3  10.093 ± 0.345  ops/ms
ClientGrpc.listUser                        thrpt       3   7.881 ± 0.976  ops/ms
ClientGrpc.createUser                       avgt       3   3.216 ± 1.167   ms/op
ClientGrpc.existUser                        avgt       3   3.058 ± 0.853   ms/op
ClientGrpc.getUser                          avgt       3   3.143 ± 0.576   ms/op
ClientGrpc.listUser                         avgt       3   4.031 ± 0.736   ms/op
ClientGrpc.createUser                     sample  307269   3.127 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.581           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.813           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.028           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.174           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.804           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.689           ms/op
ClientGrpc.existUser                      sample  312606   3.069 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.662           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.047           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.961           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.249           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.751           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.817           ms/op
ClientGrpc.getUser                        sample  304105   3.157 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.667           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.146           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.944           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.895           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.668           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.185           ms/op
ClientGrpc.listUser                       sample  231678   4.144 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.028           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.291           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.234           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.512           ms/op
