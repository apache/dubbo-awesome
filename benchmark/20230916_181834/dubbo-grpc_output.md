# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.186 ops/ms
# Warmup Iteration   2: 8.913 ops/ms
# Warmup Iteration   3: 9.897 ops/ms
Iteration   1: 10.228 ops/ms
Iteration   2: 10.446 ops/ms
Iteration   3: 10.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.295 ±(99.9%) 2.387 ops/ms [Average]
  (min, avg, max) = (10.212, 10.295, 10.446), stdev = 0.131
  CI (99.9%): [7.908, 12.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.142 ops/ms
# Warmup Iteration   2: 10.467 ops/ms
# Warmup Iteration   3: 10.588 ops/ms
Iteration   1: 10.840 ops/ms
Iteration   2: 10.898 ops/ms
Iteration   3: 10.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.861 ±(99.9%) 0.589 ops/ms [Average]
  (min, avg, max) = (10.840, 10.861, 10.898), stdev = 0.032
  CI (99.9%): [10.272, 11.450] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.083 ops/ms
# Warmup Iteration   2: 9.915 ops/ms
# Warmup Iteration   3: 10.281 ops/ms
Iteration   1: 10.186 ops/ms
Iteration   2: 10.481 ops/ms
Iteration   3: 10.534 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.401 ±(99.9%) 3.419 ops/ms [Average]
  (min, avg, max) = (10.186, 10.401, 10.534), stdev = 0.187
  CI (99.9%): [6.982, 13.820] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.440 ops/ms
# Warmup Iteration   2: 7.925 ops/ms
# Warmup Iteration   3: 8.169 ops/ms
Iteration   1: 8.302 ops/ms
Iteration   2: 8.396 ops/ms
Iteration   3: 8.209 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.302 ±(99.9%) 1.709 ops/ms [Average]
  (min, avg, max) = (8.209, 8.302, 8.396), stdev = 0.094
  CI (99.9%): [6.594, 10.011] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.190 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.002 ms/op
Iteration   1: 3.109 ±(99.9%) 0.003 ms/op
Iteration   2: 3.120 ±(99.9%) 0.002 ms/op
Iteration   3: 3.141 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.123 ±(99.9%) 0.294 ms/op [Average]
  (min, avg, max) = (3.109, 3.123, 3.141), stdev = 0.016
  CI (99.9%): [2.830, 3.417] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.497 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.003 ms/op
Iteration   1: 2.977 ±(99.9%) 0.003 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.995 ±(99.9%) 0.406 ms/op [Average]
  (min, avg, max) = (2.977, 2.995, 3.020), stdev = 0.022
  CI (99.9%): [2.589, 3.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.184 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.005 ms/op
Iteration   1: 3.170 ±(99.9%) 0.001 ms/op
Iteration   2: 3.080 ±(99.9%) 0.003 ms/op
Iteration   3: 3.136 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.129 ±(99.9%) 0.832 ms/op [Average]
  (min, avg, max) = (3.080, 3.129, 3.170), stdev = 0.046
  CI (99.9%): [2.297, 3.961] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.512 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.043 ms/op
Iteration   1: 3.864 ±(99.9%) 0.019 ms/op
Iteration   2: 3.751 ±(99.9%) 0.035 ms/op
Iteration   3: 3.841 ±(99.9%) 0.047 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.819 ±(99.9%) 1.095 ms/op [Average]
  (min, avg, max) = (3.751, 3.819, 3.864), stdev = 0.060
  CI (99.9%): [2.724, 4.913] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.005 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.827 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.847 ms/op
                 createUser·p0.9999: 12.751 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   2: 3.174 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.932 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.291 ms/op
                 createUser·p0.999:  7.073 ms/op
                 createUser·p0.9999: 17.231 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.602 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  11.738 ms/op
                 createUser·p0.9999: 23.800 ms/op
                 createUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305445
  mean =      3.141 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9735 
    [ 2.500,  5.000) = 294063 
    [ 5.000,  7.500) = 1183 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.602 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      9.364 ms/op
     p(99.9900) =     21.427 ms/op
     p(99.9990) =     23.984 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.948 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.005 ms/op
Iteration   1: 2.958 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.465 ms/op
                 existUser·p0.999:  8.080 ms/op
                 existUser·p0.9999: 11.884 ms/op
                 existUser·p1.00:   12.927 ms/op

Iteration   2: 2.998 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.104 ms/op
                 existUser·p0.9999: 13.816 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   3: 3.008 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  6.579 ms/op
                 existUser·p0.9999: 15.623 ms/op
                 existUser·p1.00:   16.220 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321411
  mean =      2.988 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1553 
    [ 1.250,  2.500) = 20862 
    [ 2.500,  3.750) = 284701 
    [ 3.750,  5.000) = 13056 
    [ 5.000,  6.250) = 724 
    [ 6.250,  7.500) = 244 
    [ 7.500,  8.750) = 100 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.173 ms/op
     p(99.9900) =     14.563 ms/op
     p(99.9990) =     16.128 ms/op
     p(99.9999) =     16.220 ms/op
    p(100.0000) =     16.220 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.101 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.365 ms/op
                 getUser·p0.9999: 18.211 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   2: 3.180 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.346 ms/op
                 getUser·p0.9999: 19.956 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.803 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  7.791 ms/op
                 getUser·p0.9999: 20.571 ms/op
                 getUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305221
  mean =      3.143 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8696 
    [ 2.500,  5.000) = 294977 
    [ 5.000,  7.500) = 1255 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.422 ms/op
     p(99.9900) =     19.939 ms/op
     p(99.9990) =     20.965 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.550 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.909 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.008 ms/op
Iteration   1: 3.893 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.362 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  11.807 ms/op
                 listUser·p0.9999: 13.382 ms/op
                 listUser·p1.00:   15.139 ms/op

Iteration   2: 3.782 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.262 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  12.720 ms/op
                 listUser·p0.9999: 14.893 ms/op
                 listUser·p1.00:   15.155 ms/op

Iteration   3: 3.904 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.521 ms/op
                 listUser·p0.999:  12.009 ms/op
                 listUser·p0.9999: 15.512 ms/op
                 listUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248835
  mean =      3.859 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3409 
    [ 2.500,  3.750) = 116385 
    [ 3.750,  5.000) = 114721 
    [ 5.000,  6.250) = 9386 
    [ 6.250,  7.500) = 4005 
    [ 7.500,  8.750) = 341 
    [ 8.750, 10.000) = 149 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 173 
    [12.500, 13.750) = 120 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.262 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      5.243 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     15.110 ms/op
     p(99.9990) =     16.286 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.295 ± 2.387  ops/ms
ClientGrpc.existUser                       thrpt       3  10.861 ± 0.589  ops/ms
ClientGrpc.getUser                         thrpt       3  10.401 ± 3.419  ops/ms
ClientGrpc.listUser                        thrpt       3   8.302 ± 1.709  ops/ms
ClientGrpc.createUser                       avgt       3   3.123 ± 0.294   ms/op
ClientGrpc.existUser                        avgt       3   2.995 ± 0.406   ms/op
ClientGrpc.getUser                          avgt       3   3.129 ± 0.832   ms/op
ClientGrpc.listUser                         avgt       3   3.819 ± 1.095   ms/op
ClientGrpc.createUser                     sample  305445   3.141 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.602           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.097           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.364           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.427           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.052           ms/op
ClientGrpc.existUser                      sample  321411   2.988 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.669           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.173           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.563           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.220           ms/op
ClientGrpc.getUser                        sample  305221   3.143 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.713           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.891           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.422           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.939           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.201           ms/op
ClientGrpc.listUser                       sample  248835   3.859 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.262           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.350           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.108           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          15.110           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          17.105           ms/op
