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
# Warmup Iteration   1: 4.651 ops/ms
# Warmup Iteration   2: 9.429 ops/ms
# Warmup Iteration   3: 10.000 ops/ms
Iteration   1: 10.427 ops/ms
Iteration   2: 10.540 ops/ms
Iteration   3: 10.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.406 ±(99.9%) 2.664 ops/ms [Average]
  (min, avg, max) = (10.250, 10.406, 10.540), stdev = 0.146
  CI (99.9%): [7.742, 13.070] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.819 ops/ms
# Warmup Iteration   2: 10.761 ops/ms
# Warmup Iteration   3: 10.426 ops/ms
Iteration   1: 10.874 ops/ms
Iteration   2: 10.743 ops/ms
Iteration   3: 10.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.802 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (10.743, 10.802, 10.874), stdev = 0.066
  CI (99.9%): [9.591, 12.014] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.485 ops/ms
# Warmup Iteration   2: 10.255 ops/ms
# Warmup Iteration   3: 10.492 ops/ms
Iteration   1: 10.315 ops/ms
Iteration   2: 10.662 ops/ms
Iteration   3: 10.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.382 ±(99.9%) 4.627 ops/ms [Average]
  (min, avg, max) = (10.168, 10.382, 10.662), stdev = 0.254
  CI (99.9%): [5.755, 15.009] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.701 ops/ms
# Warmup Iteration   2: 7.835 ops/ms
# Warmup Iteration   3: 7.866 ops/ms
Iteration   1: 8.245 ops/ms
Iteration   2: 7.922 ops/ms
Iteration   3: 7.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.055 ±(99.9%) 3.083 ops/ms [Average]
  (min, avg, max) = (7.922, 8.055, 8.245), stdev = 0.169
  CI (99.9%): [4.972, 11.138] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.144 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.109 ±(99.9%) 0.010 ms/op
Iteration   1: 3.097 ±(99.9%) 0.002 ms/op
Iteration   2: 3.173 ±(99.9%) 0.001 ms/op
Iteration   3: 3.124 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.131 ±(99.9%) 0.705 ms/op [Average]
  (min, avg, max) = (3.097, 3.131, 3.173), stdev = 0.039
  CI (99.9%): [2.427, 3.836] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.530 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.874 ±(99.9%) 0.003 ms/op
Iteration   1: 2.944 ±(99.9%) 0.005 ms/op
Iteration   2: 2.977 ±(99.9%) 0.002 ms/op
Iteration   3: 2.939 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.953 ±(99.9%) 0.377 ms/op [Average]
  (min, avg, max) = (2.939, 2.953, 2.977), stdev = 0.021
  CI (99.9%): [2.576, 3.330] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 3.012 ±(99.9%) 0.002 ms/op
Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.021 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (2.962, 3.021, 3.089), stdev = 0.064
  CI (99.9%): [1.857, 4.185] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.569 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.011 ms/op
Iteration   1: 3.996 ±(99.9%) 0.006 ms/op
Iteration   2: 4.077 ±(99.9%) 0.012 ms/op
Iteration   3: 3.968 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.014 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (3.968, 4.014, 4.077), stdev = 0.057
  CI (99.9%): [2.979, 5.049] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.140 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.007 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  6.405 ms/op
                 createUser·p0.9999: 14.719 ms/op
                 createUser·p1.00:   16.433 ms/op

Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.683 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  10.797 ms/op
                 createUser·p0.9999: 16.692 ms/op
                 createUser·p1.00:   19.300 ms/op

Iteration   3: 3.080 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.272 ms/op
                 createUser·p0.9999: 18.350 ms/op
                 createUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309864
  mean =      3.097 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1353 
    [ 1.250,  2.500) = 26557 
    [ 2.500,  3.750) = 250374 
    [ 3.750,  5.000) = 30480 
    [ 5.000,  6.250) = 506 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.454 ms/op
     p(99.9900) =     18.055 ms/op
     p(99.9990) =     18.511 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.851 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
Iteration   1: 2.937 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  6.654 ms/op
                 existUser·p0.9999: 12.312 ms/op
                 existUser·p1.00:   12.681 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.191 ms/op
                 existUser·p0.9999: 13.015 ms/op
                 existUser·p1.00:   13.173 ms/op

Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.174 ms/op
                 existUser·p0.999:  9.877 ms/op
                 existUser·p0.9999: 15.665 ms/op
                 existUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324025
  mean =      2.962 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1876 
    [ 1.250,  2.500) = 45597 
    [ 2.500,  3.750) = 260651 
    [ 3.750,  5.000) = 14898 
    [ 5.000,  6.250) = 511 
    [ 6.250,  7.500) = 174 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     14.185 ms/op
     p(99.9990) =     16.126 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.320 ms/op
                 getUser·p0.9999: 17.623 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.791 ms/op
                 getUser·p0.9999: 19.586 ms/op
                 getUser·p1.00:   19.988 ms/op

Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.472 ms/op
                 getUser·p0.9999: 20.447 ms/op
                 getUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313518
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27302 
    [ 2.500,  5.000) = 285187 
    [ 5.000,  7.500) = 772 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.815 ms/op
     p(99.9900) =     20.108 ms/op
     p(99.9990) =     20.902 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 5.115 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.011 ms/op
Iteration   1: 4.060 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.699 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.196 ms/op
                 listUser·p0.9999: 16.068 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 3.909 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.389 ms/op
                 listUser·p0.9999: 22.991 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   3: 3.986 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.325 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  14.527 ms/op
                 listUser·p0.9999: 17.203 ms/op
                 listUser·p1.00:   17.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240826
  mean =      3.984 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3138 
    [ 2.500,  5.000) = 210062 
    [ 5.000,  7.500) = 26531 
    [ 7.500, 10.000) = 650 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     13.929 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     24.470 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.406 ± 2.664  ops/ms
ClientGrpc.existUser                       thrpt       3  10.802 ± 1.212  ops/ms
ClientGrpc.getUser                         thrpt       3  10.382 ± 4.627  ops/ms
ClientGrpc.listUser                        thrpt       3   8.055 ± 3.083  ops/ms
ClientGrpc.createUser                       avgt       3   3.131 ± 0.705   ms/op
ClientGrpc.existUser                        avgt       3   2.953 ± 0.377   ms/op
ClientGrpc.getUser                          avgt       3   3.021 ± 1.164   ms/op
ClientGrpc.listUser                         avgt       3   4.014 ± 1.035   ms/op
ClientGrpc.createUser                     sample  309864   3.097 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.652           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.454           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.055           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.300           ms/op
ClientGrpc.existUser                      sample  324025   2.962 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.645           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.744           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.406           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.185           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.286           ms/op
ClientGrpc.getUser                        sample  313518   3.060 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.593           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.815           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.108           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.037           ms/op
ClientGrpc.listUser                       sample  240826   3.984 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.699           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.929           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.692           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.642           ms/op
