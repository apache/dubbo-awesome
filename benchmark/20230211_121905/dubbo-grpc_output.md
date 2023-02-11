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
# Warmup Iteration   1: 4.510 ops/ms
# Warmup Iteration   2: 9.273 ops/ms
# Warmup Iteration   3: 10.295 ops/ms
Iteration   1: 10.854 ops/ms
Iteration   2: 10.498 ops/ms
Iteration   3: 10.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.509 ±(99.9%) 6.183 ops/ms [Average]
  (min, avg, max) = (10.176, 10.509, 10.854), stdev = 0.339
  CI (99.9%): [4.326, 16.692] (assumes normal distribution)


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
# Warmup Iteration   1: 7.843 ops/ms
# Warmup Iteration   2: 10.215 ops/ms
# Warmup Iteration   3: 10.497 ops/ms
Iteration   1: 10.592 ops/ms
Iteration   2: 10.841 ops/ms
Iteration   3: 10.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.755 ±(99.9%) 2.566 ops/ms [Average]
  (min, avg, max) = (10.592, 10.755, 10.841), stdev = 0.141
  CI (99.9%): [8.188, 13.321] (assumes normal distribution)


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
# Warmup Iteration   1: 7.456 ops/ms
# Warmup Iteration   2: 10.328 ops/ms
# Warmup Iteration   3: 10.359 ops/ms
Iteration   1: 10.677 ops/ms
Iteration   2: 10.245 ops/ms
Iteration   3: 10.400 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.440 ±(99.9%) 3.989 ops/ms [Average]
  (min, avg, max) = (10.245, 10.440, 10.677), stdev = 0.219
  CI (99.9%): [6.452, 14.429] (assumes normal distribution)


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
# Warmup Iteration   1: 6.626 ops/ms
# Warmup Iteration   2: 7.693 ops/ms
# Warmup Iteration   3: 7.982 ops/ms
Iteration   1: 7.897 ops/ms
Iteration   2: 7.996 ops/ms
Iteration   3: 8.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.020 ±(99.9%) 2.488 ops/ms [Average]
  (min, avg, max) = (7.897, 8.020, 8.167), stdev = 0.136
  CI (99.9%): [5.532, 10.508] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.004 ms/op
Iteration   1: 3.018 ±(99.9%) 0.003 ms/op
Iteration   2: 2.879 ±(99.9%) 0.002 ms/op
Iteration   3: 3.155 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.017 ±(99.9%) 2.510 ms/op [Average]
  (min, avg, max) = (2.879, 3.017, 3.155), stdev = 0.138
  CI (99.9%): [0.507, 5.528] (assumes normal distribution)


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
# Warmup Iteration   1: 3.647 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.003 ms/op
Iteration   1: 2.948 ±(99.9%) 0.003 ms/op
Iteration   2: 2.905 ±(99.9%) 0.003 ms/op
Iteration   3: 2.991 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.948 ±(99.9%) 0.790 ms/op [Average]
  (min, avg, max) = (2.905, 2.948, 2.991), stdev = 0.043
  CI (99.9%): [2.158, 3.737] (assumes normal distribution)


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.002 ms/op
Iteration   1: 3.079 ±(99.9%) 0.002 ms/op
Iteration   2: 3.121 ±(99.9%) 0.002 ms/op
Iteration   3: 3.128 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.109 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.079, 3.109, 3.128), stdev = 0.027
  CI (99.9%): [2.622, 3.596] (assumes normal distribution)


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
# Warmup Iteration   1: 4.992 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.114 ±(99.9%) 0.017 ms/op
Iteration   1: 3.998 ±(99.9%) 0.022 ms/op
Iteration   2: 3.960 ±(99.9%) 0.012 ms/op
Iteration   3: 3.978 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.979 ±(99.9%) 0.350 ms/op [Average]
  (min, avg, max) = (3.960, 3.979, 3.998), stdev = 0.019
  CI (99.9%): [3.629, 4.329] (assumes normal distribution)


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.153 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.119 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.626 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  8.056 ms/op
                 createUser·p0.9999: 12.177 ms/op
                 createUser·p1.00:   12.550 ms/op

Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.591 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.294 ms/op
                 createUser·p0.9999: 18.173 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   3: 3.144 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  12.489 ms/op
                 createUser·p0.9999: 25.952 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308636
  mean =      3.111 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24110 
    [ 2.500,  5.000) = 283453 
    [ 5.000,  7.500) = 625 
    [ 7.500, 10.000) = 187 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     24.904 ms/op
     p(99.9990) =     26.370 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.033 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
Iteration   1: 3.018 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.690 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  7.298 ms/op
                 existUser·p0.9999: 19.694 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   2: 2.876 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.652 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  5.328 ms/op
                 existUser·p0.9999: 19.399 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   3: 2.886 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.413 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.472 ms/op
                 existUser·p0.9999: 21.234 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328266
  mean =      2.925 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51444 
    [ 2.500,  5.000) = 276125 
    [ 5.000,  7.500) = 506 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      6.451 ms/op
     p(99.9900) =     20.122 ms/op
     p(99.9990) =     21.454 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.006 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.382 ms/op
                 getUser·p0.9999: 16.799 ms/op
                 getUser·p1.00:   17.269 ms/op

Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.180 ms/op
                 getUser·p0.9999: 14.406 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.667 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.397 ms/op
                 getUser·p0.9999: 15.665 ms/op
                 getUser·p1.00:   16.122 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310993
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24195 
    [ 2.500,  5.000) = 285677 
    [ 5.000,  7.500) = 805 
    [ 7.500, 10.000) = 93 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.553 ms/op
     p(99.9900) =     16.122 ms/op
     p(99.9990) =     20.305 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 5.118 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.176 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.106 ±(99.9%) 0.012 ms/op
Iteration   1: 4.095 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.678 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  18.572 ms/op
                 listUser·p0.9999: 23.952 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   2: 4.105 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.893 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 18.535 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 3.880 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.040 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  18.206 ms/op
                 listUser·p0.9999: 23.749 ms/op
                 listUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238406
  mean =      4.024 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4563 
    [ 2.500,  5.000) = 202028 
    [ 5.000,  7.500) = 30475 
    [ 7.500, 10.000) = 799 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 142 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     17.092 ms/op
     p(99.9900) =     22.742 ms/op
     p(99.9990) =     24.533 ms/op
     p(99.9999) =     24.642 ms/op
    p(100.0000) =     24.642 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.509 ± 6.183  ops/ms
ClientGrpc.existUser                       thrpt       3  10.755 ± 2.566  ops/ms
ClientGrpc.getUser                         thrpt       3  10.440 ± 3.989  ops/ms
ClientGrpc.listUser                        thrpt       3   8.020 ± 2.488  ops/ms
ClientGrpc.createUser                       avgt       3   3.017 ± 2.510   ms/op
ClientGrpc.existUser                        avgt       3   2.948 ± 0.790   ms/op
ClientGrpc.getUser                          avgt       3   3.109 ± 0.487   ms/op
ClientGrpc.listUser                         avgt       3   3.979 ± 0.350   ms/op
ClientGrpc.createUser                     sample  308636   3.111 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.591           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.110           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.904           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.509           ms/op
ClientGrpc.existUser                      sample  328266   2.925 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.413           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.451           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.122           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.692           ms/op
ClientGrpc.getUser                        sample  310993   3.085 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.617           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.553           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.122           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.594           ms/op
ClientGrpc.listUser                       sample  238406   4.024 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.678           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.092           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.742           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.642           ms/op
