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
# Warmup Iteration   1: 3.488 ops/ms
# Warmup Iteration   2: 8.299 ops/ms
# Warmup Iteration   3: 9.772 ops/ms
Iteration   1: 10.209 ops/ms
Iteration   2: 10.146 ops/ms
Iteration   3: 10.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.198 ±(99.9%) 0.850 ops/ms [Average]
  (min, avg, max) = (10.146, 10.198, 10.238), stdev = 0.047
  CI (99.9%): [9.348, 11.048] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.347 ops/ms
# Warmup Iteration   2: 10.446 ops/ms
# Warmup Iteration   3: 11.086 ops/ms
Iteration   1: 11.043 ops/ms
Iteration   2: 10.567 ops/ms
Iteration   3: 10.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.816 ±(99.9%) 4.356 ops/ms [Average]
  (min, avg, max) = (10.567, 10.816, 11.043), stdev = 0.239
  CI (99.9%): [6.460, 15.173] (assumes normal distribution)


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
# Warmup Iteration   1: 6.484 ops/ms
# Warmup Iteration   2: 9.742 ops/ms
# Warmup Iteration   3: 10.231 ops/ms
Iteration   1: 10.444 ops/ms
Iteration   2: 10.408 ops/ms
Iteration   3: 10.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.415 ±(99.9%) 0.463 ops/ms [Average]
  (min, avg, max) = (10.395, 10.415, 10.444), stdev = 0.025
  CI (99.9%): [9.952, 10.879] (assumes normal distribution)


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
# Warmup Iteration   1: 5.203 ops/ms
# Warmup Iteration   2: 7.435 ops/ms
# Warmup Iteration   3: 7.878 ops/ms
Iteration   1: 7.800 ops/ms
Iteration   2: 7.988 ops/ms
Iteration   3: 7.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.858 ±(99.9%) 2.048 ops/ms [Average]
  (min, avg, max) = (7.788, 7.858, 7.988), stdev = 0.112
  CI (99.9%): [5.810, 9.907] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.614 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.003 ms/op
Iteration   1: 3.047 ±(99.9%) 0.003 ms/op
Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
Iteration   3: 3.107 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.075 ±(99.9%) 0.555 ms/op [Average]
  (min, avg, max) = (3.047, 3.075, 3.107), stdev = 0.030
  CI (99.9%): [2.520, 3.630] (assumes normal distribution)


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
# Warmup Iteration   1: 4.154 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.002 ms/op
Iteration   1: 2.980 ±(99.9%) 0.003 ms/op
Iteration   2: 2.969 ±(99.9%) 0.002 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.993 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (2.969, 2.993, 3.028), stdev = 0.031
  CI (99.9%): [2.421, 3.564] (assumes normal distribution)


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
# Warmup Iteration   1: 4.388 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.002 ms/op
Iteration   1: 3.116 ±(99.9%) 0.005 ms/op
Iteration   2: 3.072 ±(99.9%) 0.002 ms/op
Iteration   3: 3.121 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.103 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (3.072, 3.103, 3.121), stdev = 0.027
  CI (99.9%): [2.610, 3.596] (assumes normal distribution)


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
# Warmup Iteration   1: 5.910 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.209 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.164 ±(99.9%) 0.010 ms/op
Iteration   1: 4.149 ±(99.9%) 0.015 ms/op
Iteration   2: 4.105 ±(99.9%) 0.023 ms/op
Iteration   3: 4.130 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.128 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (4.105, 4.128, 4.149), stdev = 0.022
  CI (99.9%): [3.726, 4.530] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.406 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
Iteration   1: 3.101 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.920 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  6.889 ms/op
                 createUser·p0.9999: 13.113 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   2: 3.050 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.348 ms/op
                 createUser·p0.9999: 15.286 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.032 ms/op
                 createUser·p0.9999: 18.401 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310409
  mean =      3.092 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12517 
    [ 2.500,  5.000) = 296340 
    [ 5.000,  7.500) = 1284 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.266 ms/op
     p(99.9900) =     17.692 ms/op
     p(99.9990) =     20.706 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.342 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
Iteration   1: 2.956 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.728 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.510 ms/op
                 existUser·p0.9999: 12.995 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.627 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.608 ms/op
                 existUser·p0.9999: 14.784 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 2.889 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.461 ms/op
                 existUser·p0.99:   4.087 ms/op
                 existUser·p0.999:  7.242 ms/op
                 existUser·p0.9999: 17.531 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327412
  mean =      2.933 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3237 
    [ 1.250,  2.500) = 27049 
    [ 2.500,  3.750) = 286720 
    [ 3.750,  5.000) = 9255 
    [ 5.000,  6.250) = 692 
    [ 6.250,  7.500) = 207 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.613 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.907 ms/op
     p(99.9900) =     17.170 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
Iteration   1: 3.069 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.751 ms/op
                 getUser·p0.9999: 13.456 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.578 ms/op
                 getUser·p0.9999: 15.413 ms/op
                 getUser·p1.00:   15.811 ms/op

Iteration   3: 3.152 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.854 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307085
  mean =      3.126 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 118 
    [ 1.250,  2.500) = 9172 
    [ 2.500,  3.750) = 276949 
    [ 3.750,  5.000) = 19575 
    [ 5.000,  6.250) = 713 
    [ 6.250,  7.500) = 244 
    [ 7.500,  8.750) = 110 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      7.528 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     19.034 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 5.706 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.233 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.012 ms/op
Iteration   1: 4.179 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 22.841 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   2: 4.236 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   4.035 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.034 ms/op
                 listUser·p0.99:   7.291 ms/op
                 listUser·p0.999:  15.736 ms/op
                 listUser·p0.9999: 22.362 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.179 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.021 ms/op
                 listUser·p0.99:   7.420 ms/op
                 listUser·p0.999:  17.785 ms/op
                 listUser·p0.9999: 20.819 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 228697
  mean =      4.198 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1057 
    [ 2.500,  5.000) = 199608 
    [ 5.000,  7.500) = 25849 
    [ 7.500, 10.000) = 1641 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 83 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      5.226 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     15.188 ms/op
     p(99.9900) =     22.319 ms/op
     p(99.9990) =     23.476 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.198 ± 0.850  ops/ms
ClientGrpc.existUser                       thrpt       3  10.816 ± 4.356  ops/ms
ClientGrpc.getUser                         thrpt       3  10.415 ± 0.463  ops/ms
ClientGrpc.listUser                        thrpt       3   7.858 ± 2.048  ops/ms
ClientGrpc.createUser                       avgt       3   3.075 ± 0.555   ms/op
ClientGrpc.existUser                        avgt       3   2.993 ± 0.572   ms/op
ClientGrpc.getUser                          avgt       3   3.103 ± 0.493   ms/op
ClientGrpc.listUser                         avgt       3   4.128 ± 0.402   ms/op
ClientGrpc.createUser                     sample  310409   3.092 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.715           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.266           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.692           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.742           ms/op
ClientGrpc.existUser                      sample  327412   2.933 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.568           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.941           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.613           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.907           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.170           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.859           ms/op
ClientGrpc.getUser                        sample  307085   3.126 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.880           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.528           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.203           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.137           ms/op
ClientGrpc.listUser                       sample  228697   4.198 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.124           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.006           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.226           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.455           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.188           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.319           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.527           ms/op
