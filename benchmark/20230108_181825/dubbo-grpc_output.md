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
# Warmup Iteration   1: 4.147 ops/ms
# Warmup Iteration   2: 9.180 ops/ms
# Warmup Iteration   3: 10.069 ops/ms
Iteration   1: 10.334 ops/ms
Iteration   2: 10.580 ops/ms
Iteration   3: 10.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.341 ±(99.9%) 4.314 ops/ms [Average]
  (min, avg, max) = (10.107, 10.341, 10.580), stdev = 0.236
  CI (99.9%): [6.027, 14.654] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.508 ops/ms
# Warmup Iteration   2: 10.378 ops/ms
# Warmup Iteration   3: 10.718 ops/ms
Iteration   1: 10.510 ops/ms
Iteration   2: 10.967 ops/ms
Iteration   3: 10.826 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.768 ±(99.9%) 4.264 ops/ms [Average]
  (min, avg, max) = (10.510, 10.768, 10.967), stdev = 0.234
  CI (99.9%): [6.504, 15.031] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.877 ops/ms
# Warmup Iteration   2: 10.004 ops/ms
# Warmup Iteration   3: 10.452 ops/ms
Iteration   1: 10.376 ops/ms
Iteration   2: 10.352 ops/ms
Iteration   3: 10.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.364 ±(99.9%) 0.219 ops/ms [Average]
  (min, avg, max) = (10.352, 10.364, 10.376), stdev = 0.012
  CI (99.9%): [10.144, 10.583] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.768 ops/ms
# Warmup Iteration   2: 7.747 ops/ms
# Warmup Iteration   3: 7.823 ops/ms
Iteration   1: 8.031 ops/ms
Iteration   2: 7.675 ops/ms
Iteration   3: 7.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.870 ±(99.9%) 3.296 ops/ms [Average]
  (min, avg, max) = (7.675, 7.870, 8.031), stdev = 0.181
  CI (99.9%): [4.574, 11.167] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.252 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.002 ms/op
Iteration   1: 3.229 ±(99.9%) 0.003 ms/op
Iteration   2: 3.209 ±(99.9%) 0.002 ms/op
Iteration   3: 3.231 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.223 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.209, 3.223, 3.231), stdev = 0.012
  CI (99.9%): [3.006, 3.440] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.928 ±(99.9%) 0.004 ms/op
Iteration   1: 2.999 ±(99.9%) 0.002 ms/op
Iteration   2: 3.023 ±(99.9%) 0.002 ms/op
Iteration   3: 2.941 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.987 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (2.941, 2.987, 3.023), stdev = 0.042
  CI (99.9%): [2.217, 3.758] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.095 ±(99.9%) 0.004 ms/op
Iteration   1: 3.157 ±(99.9%) 0.003 ms/op
Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.125 ±(99.9%) 0.521 ms/op [Average]
  (min, avg, max) = (3.102, 3.125, 3.157), stdev = 0.029
  CI (99.9%): [2.603, 3.646] (assumes normal distribution)


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
# Warmup Iteration   1: 5.230 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.029 ms/op
Iteration   1: 4.070 ±(99.9%) 0.008 ms/op
Iteration   2: 4.037 ±(99.9%) 0.005 ms/op
Iteration   3: 4.012 ±(99.9%) 0.035 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.040 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (4.012, 4.040, 4.070), stdev = 0.029
  CI (99.9%): [3.517, 4.563] (assumes normal distribution)


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
# Warmup Iteration   1: 4.314 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.216 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.007 ms/op
Iteration   1: 3.178 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.989 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.045 ms/op
                 createUser·p0.9999: 18.899 ms/op
                 createUser·p1.00:   20.906 ms/op

Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  10.779 ms/op
                 createUser·p0.9999: 17.619 ms/op
                 createUser·p1.00:   18.383 ms/op

Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  9.190 ms/op
                 createUser·p0.9999: 20.440 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304249
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25928 
    [ 2.500,  5.000) = 277354 
    [ 5.000,  7.500) = 533 
    [ 7.500, 10.000) = 182 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      9.028 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 2.983 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.308 ms/op
                 existUser·p0.9999: 13.367 ms/op
                 existUser·p1.00:   13.828 ms/op

Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  5.063 ms/op
                 existUser·p0.9999: 14.526 ms/op
                 existUser·p1.00:   16.089 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.485 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  8.441 ms/op
                 existUser·p0.9999: 27.270 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319133
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50578 
    [ 2.500,  5.000) = 267834 
    [ 5.000,  7.500) = 495 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      6.791 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     27.656 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 4.173 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.165 ±(99.9%) 0.006 ms/op
Iteration   1: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  8.275 ms/op
                 getUser·p0.9999: 14.735 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  5.991 ms/op
                 getUser·p0.9999: 14.582 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.151 ms/op
                 getUser·p0.9999: 18.013 ms/op
                 getUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310349
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 631 
    [ 1.250,  2.500) = 25582 
    [ 2.500,  3.750) = 259464 
    [ 3.750,  5.000) = 23271 
    [ 5.000,  6.250) = 691 
    [ 6.250,  7.500) = 355 
    [ 7.500,  8.750) = 144 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 87 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.823 ms/op
     p(99.9900) =     17.202 ms/op
     p(99.9990) =     18.376 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 5.373 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.155 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.011 ms/op
Iteration   1: 4.123 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.264 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.128 ms/op
                 listUser·p0.9999: 15.618 ms/op
                 listUser·p1.00:   15.991 ms/op

Iteration   2: 3.951 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  16.357 ms/op
                 listUser·p0.9999: 22.771 ms/op
                 listUser·p1.00:   23.101 ms/op

Iteration   3: 3.943 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.652 ms/op
                 listUser·p0.9999: 28.271 ms/op
                 listUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239780
  mean =      4.004 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1804 
    [ 2.500,  5.000) = 212763 
    [ 5.000,  7.500) = 23940 
    [ 7.500, 10.000) = 841 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     27.820 ms/op
     p(99.9990) =     28.666 ms/op
     p(99.9999) =     28.803 ms/op
    p(100.0000) =     28.803 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.341 ± 4.314  ops/ms
ClientGrpc.existUser                       thrpt       3  10.768 ± 4.264  ops/ms
ClientGrpc.getUser                         thrpt       3  10.364 ± 0.219  ops/ms
ClientGrpc.listUser                        thrpt       3   7.870 ± 3.296  ops/ms
ClientGrpc.createUser                       avgt       3   3.223 ± 0.217   ms/op
ClientGrpc.existUser                        avgt       3   2.987 ± 0.771   ms/op
ClientGrpc.getUser                          avgt       3   3.125 ± 0.521   ms/op
ClientGrpc.listUser                         avgt       3   4.040 ± 0.523   ms/op
ClientGrpc.createUser                     sample  304249   3.155 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.616           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.028           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.661           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.906           ms/op
ClientGrpc.existUser                      sample  319133   3.006 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.485           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.903           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.791           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.247           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.377           ms/op
ClientGrpc.getUser                        sample  310349   3.092 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.806           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.823           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.202           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.776           ms/op
ClientGrpc.listUser                       sample  239780   4.004 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.877           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.820           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.803           ms/op
