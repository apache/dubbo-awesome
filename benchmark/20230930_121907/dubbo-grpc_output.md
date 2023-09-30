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
# Warmup Iteration   1: 4.258 ops/ms
# Warmup Iteration   2: 8.701 ops/ms
# Warmup Iteration   3: 9.681 ops/ms
Iteration   1: 10.115 ops/ms
Iteration   2: 10.293 ops/ms
Iteration   3: 10.178 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.195 ±(99.9%) 1.645 ops/ms [Average]
  (min, avg, max) = (10.115, 10.195, 10.293), stdev = 0.090
  CI (99.9%): [8.550, 11.840] (assumes normal distribution)


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
# Warmup Iteration   1: 7.435 ops/ms
# Warmup Iteration   2: 10.052 ops/ms
# Warmup Iteration   3: 10.582 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.715 ops/ms
Iteration   3: 10.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.603 ±(99.9%) 2.705 ops/ms [Average]
  (min, avg, max) = (10.434, 10.603, 10.715), stdev = 0.148
  CI (99.9%): [7.898, 13.307] (assumes normal distribution)


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
# Warmup Iteration   1: 6.444 ops/ms
# Warmup Iteration   2: 9.749 ops/ms
# Warmup Iteration   3: 10.088 ops/ms
Iteration   1: 10.185 ops/ms
Iteration   2: 10.087 ops/ms
Iteration   3: 10.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.136 ±(99.9%) 0.888 ops/ms [Average]
  (min, avg, max) = (10.087, 10.136, 10.185), stdev = 0.049
  CI (99.9%): [9.248, 11.024] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.918 ops/ms
# Warmup Iteration   2: 7.387 ops/ms
# Warmup Iteration   3: 7.998 ops/ms
Iteration   1: 8.201 ops/ms
Iteration   2: 7.875 ops/ms
Iteration   3: 8.152 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.076 ±(99.9%) 3.206 ops/ms [Average]
  (min, avg, max) = (7.875, 8.076, 8.201), stdev = 0.176
  CI (99.9%): [4.869, 11.282] (assumes normal distribution)


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
# Warmup Iteration   1: 4.497 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.245 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.248 ±(99.9%) 0.002 ms/op
Iteration   1: 3.180 ±(99.9%) 0.005 ms/op
Iteration   2: 3.146 ±(99.9%) 0.002 ms/op
Iteration   3: 3.202 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.176 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (3.146, 3.176, 3.202), stdev = 0.028
  CI (99.9%): [2.666, 3.686] (assumes normal distribution)


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
# Warmup Iteration   1: 4.026 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.002 ms/op
Iteration   1: 2.989 ±(99.9%) 0.002 ms/op
Iteration   2: 3.105 ±(99.9%) 0.002 ms/op
Iteration   3: 2.982 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.026 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (2.982, 3.026, 3.105), stdev = 0.069
  CI (99.9%): [1.764, 4.287] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.424 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.223 ±(99.9%) 0.002 ms/op
Iteration   1: 3.138 ±(99.9%) 0.003 ms/op
Iteration   2: 3.190 ±(99.9%) 0.002 ms/op
Iteration   3: 3.171 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.166 ±(99.9%) 0.478 ms/op [Average]
  (min, avg, max) = (3.138, 3.166, 3.190), stdev = 0.026
  CI (99.9%): [2.688, 3.644] (assumes normal distribution)


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
# Warmup Iteration   1: 5.365 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.059 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.035 ms/op
Iteration   1: 3.951 ±(99.9%) 0.006 ms/op
Iteration   2: 3.950 ±(99.9%) 0.026 ms/op
Iteration   3: 3.930 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.944 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (3.930, 3.944, 3.951), stdev = 0.012
  CI (99.9%): [3.729, 4.159] (assumes normal distribution)


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
# Warmup Iteration   1: 4.348 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
Iteration   1: 3.162 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.756 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  6.978 ms/op
                 createUser·p0.9999: 17.097 ms/op
                 createUser·p1.00:   17.629 ms/op

Iteration   2: 3.179 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  8.350 ms/op
                 createUser·p0.9999: 19.200 ms/op
                 createUser·p1.00:   19.562 ms/op

Iteration   3: 3.207 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.845 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  12.001 ms/op
                 createUser·p0.9999: 23.298 ms/op
                 createUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301530
  mean =      3.183 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6723 
    [ 2.500,  5.000) = 293211 
    [ 5.000,  7.500) = 1070 
    [ 7.500, 10.000) = 203 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     10.288 ms/op
     p(99.9900) =     22.993 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 3.941 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.005 ms/op
Iteration   1: 3.045 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.520 ms/op
                 existUser·p0.9999: 16.294 ms/op
                 existUser·p1.00:   16.761 ms/op

Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 14.198 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  10.030 ms/op
                 existUser·p0.9999: 15.221 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311913
  mean =      3.076 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 222 
    [ 1.250,  2.500) = 13349 
    [ 2.500,  3.750) = 279407 
    [ 3.750,  5.000) = 17548 
    [ 5.000,  6.250) = 568 
    [ 6.250,  7.500) = 317 
    [ 7.500,  8.750) = 157 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.797 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     15.807 ms/op
     p(99.9990) =     16.706 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.521 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.007 ms/op
Iteration   1: 3.175 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.530 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  13.442 ms/op
                 getUser·p0.9999: 17.821 ms/op
                 getUser·p1.00:   18.514 ms/op

Iteration   2: 3.166 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.949 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  7.790 ms/op
                 getUser·p0.9999: 19.130 ms/op
                 getUser·p1.00:   19.857 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.000 ms/op
                 getUser·p0.9999: 23.981 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303346
  mean =      3.166 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9078 
    [ 2.500,  5.000) = 292226 
    [ 5.000,  7.500) = 1598 
    [ 7.500, 10.000) = 172 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.530 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.596 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     24.280 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 6.130 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.129 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.010 ms/op
Iteration   1: 3.939 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.430 ms/op
                 listUser·p0.9999: 19.460 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 3.920 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.299 ms/op
                 listUser·p0.9999: 17.258 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   3: 3.974 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.812 ms/op
                 listUser·p0.9999: 18.511 ms/op
                 listUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243375
  mean =      3.944 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1268 
    [ 2.500,  5.000) = 228789 
    [ 5.000,  7.500) = 11997 
    [ 7.500, 10.000) = 806 
    [10.000, 12.500) = 113 
    [12.500, 15.000) = 223 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     19.158 ms/op
     p(99.9990) =     20.962 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.195 ± 1.645  ops/ms
ClientGrpc.existUser                       thrpt       3  10.603 ± 2.705  ops/ms
ClientGrpc.getUser                         thrpt       3  10.136 ± 0.888  ops/ms
ClientGrpc.listUser                        thrpt       3   8.076 ± 3.206  ops/ms
ClientGrpc.createUser                       avgt       3   3.176 ± 0.510   ms/op
ClientGrpc.existUser                        avgt       3   3.026 ± 1.261   ms/op
ClientGrpc.getUser                          avgt       3   3.166 ± 0.478   ms/op
ClientGrpc.listUser                         avgt       3   3.944 ± 0.215   ms/op
ClientGrpc.createUser                     sample  301530   3.183 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.643           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.895           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.288           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.993           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.478           ms/op
ClientGrpc.existUser                      sample  311913   3.076 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.797           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.355           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.807           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.810           ms/op
ClientGrpc.getUser                        sample  303346   3.166 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.530           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.596           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.266           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.281           ms/op
ClientGrpc.listUser                       sample  243375   3.944 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.979           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.424           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.270           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.158           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.398           ms/op
