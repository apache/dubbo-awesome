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
# Warmup Iteration   1: 3.905 ops/ms
# Warmup Iteration   2: 8.930 ops/ms
# Warmup Iteration   3: 10.058 ops/ms
Iteration   1: 10.523 ops/ms
Iteration   2: 10.440 ops/ms
Iteration   3: 10.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.399 ±(99.9%) 2.712 ops/ms [Average]
  (min, avg, max) = (10.234, 10.399, 10.523), stdev = 0.149
  CI (99.9%): [7.687, 13.110] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.343 ops/ms
# Warmup Iteration   2: 10.237 ops/ms
# Warmup Iteration   3: 10.728 ops/ms
Iteration   1: 10.904 ops/ms
Iteration   2: 11.042 ops/ms
Iteration   3: 11.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.017 ±(99.9%) 1.878 ops/ms [Average]
  (min, avg, max) = (10.904, 11.017, 11.105), stdev = 0.103
  CI (99.9%): [9.139, 12.894] (assumes normal distribution)


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
# Warmup Iteration   1: 6.931 ops/ms
# Warmup Iteration   2: 9.917 ops/ms
# Warmup Iteration   3: 10.442 ops/ms
Iteration   1: 10.317 ops/ms
Iteration   2: 10.511 ops/ms
Iteration   3: 10.297 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.375 ±(99.9%) 2.155 ops/ms [Average]
  (min, avg, max) = (10.297, 10.375, 10.511), stdev = 0.118
  CI (99.9%): [8.219, 12.530] (assumes normal distribution)


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
# Warmup Iteration   1: 5.401 ops/ms
# Warmup Iteration   2: 8.016 ops/ms
# Warmup Iteration   3: 8.058 ops/ms
Iteration   1: 8.118 ops/ms
Iteration   2: 8.231 ops/ms
Iteration   3: 8.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.130 ±(99.9%) 1.760 ops/ms [Average]
  (min, avg, max) = (8.039, 8.130, 8.231), stdev = 0.096
  CI (99.9%): [6.369, 9.890] (assumes normal distribution)


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
# Warmup Iteration   1: 4.453 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.351 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.003 ms/op
Iteration   1: 3.061 ±(99.9%) 0.005 ms/op
Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
Iteration   3: 2.986 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.044 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (2.986, 3.044, 3.086), stdev = 0.052
  CI (99.9%): [2.095, 3.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.003 ms/op
Iteration   1: 2.902 ±(99.9%) 0.003 ms/op
Iteration   2: 2.907 ±(99.9%) 0.002 ms/op
Iteration   3: 2.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.915 ±(99.9%) 0.349 ms/op [Average]
  (min, avg, max) = (2.902, 2.915, 2.937), stdev = 0.019
  CI (99.9%): [2.567, 3.264] (assumes normal distribution)


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.133 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.003 ms/op
Iteration   1: 3.025 ±(99.9%) 0.004 ms/op
Iteration   2: 3.072 ±(99.9%) 0.001 ms/op
Iteration   3: 3.037 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.045 ±(99.9%) 0.444 ms/op [Average]
  (min, avg, max) = (3.025, 3.045, 3.072), stdev = 0.024
  CI (99.9%): [2.601, 3.489] (assumes normal distribution)


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
# Warmup Iteration   1: 5.589 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.010 ms/op
Iteration   1: 3.936 ±(99.9%) 0.012 ms/op
Iteration   2: 3.917 ±(99.9%) 0.012 ms/op
Iteration   3: 3.829 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.894 ±(99.9%) 1.041 ms/op [Average]
  (min, avg, max) = (3.829, 3.894, 3.936), stdev = 0.057
  CI (99.9%): [2.853, 4.935] (assumes normal distribution)


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
Iteration   1: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  6.610 ms/op
                 createUser·p0.9999: 19.447 ms/op
                 createUser·p1.00:   19.825 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.459 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.883 ms/op
                 createUser·p0.9999: 19.628 ms/op
                 createUser·p1.00:   20.152 ms/op

Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.615 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.630 ms/op
                 createUser·p0.9999: 21.722 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313690
  mean =      3.062 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16394 
    [ 2.500,  5.000) = 295921 
    [ 5.000,  7.500) = 1096 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.189 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     23.022 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
Iteration   1: 2.926 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.576 ms/op
                 existUser·p0.9999: 13.566 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 2.946 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.920 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.107 ms/op
                 existUser·p0.999:  10.755 ms/op
                 existUser·p0.9999: 13.847 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   3: 2.925 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  6.425 ms/op
                 existUser·p0.9999: 18.022 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327175
  mean =      2.932 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 740 
    [ 1.250,  2.500) = 26073 
    [ 2.500,  3.750) = 291691 
    [ 3.750,  5.000) = 7831 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 27 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.510 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      7.193 ms/op
     p(99.9900) =     16.225 ms/op
     p(99.9990) =     18.225 ms/op
     p(99.9999) =     18.678 ms/op
    p(100.0000) =     18.678 ms/op


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  7.103 ms/op
                 getUser·p0.9999: 14.926 ms/op
                 getUser·p1.00:   15.270 ms/op

Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  7.118 ms/op
                 getUser·p0.9999: 26.083 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.693 ms/op
                 getUser·p0.9999: 18.448 ms/op
                 getUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315201
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24020 
    [ 2.500,  5.000) = 289490 
    [ 5.000,  7.500) = 1414 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      7.215 ms/op
     p(99.9900) =     25.180 ms/op
     p(99.9990) =     26.794 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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
# Warmup Iteration   1: 5.761 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.011 ms/op
Iteration   1: 3.967 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  14.522 ms/op
                 listUser·p0.9999: 17.330 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   2: 4.101 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  19.434 ms/op
                 listUser·p0.9999: 22.643 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   3: 3.973 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  19.282 ms/op
                 listUser·p0.9999: 23.101 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239147
  mean =      4.013 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1648 
    [ 2.500,  5.000) = 212986 
    [ 5.000,  7.500) = 22604 
    [ 7.500, 10.000) = 1209 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     16.592 ms/op
     p(99.9900) =     22.711 ms/op
     p(99.9990) =     24.110 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.399 ± 2.712  ops/ms
ClientGrpc.existUser                       thrpt       3  11.017 ± 1.878  ops/ms
ClientGrpc.getUser                         thrpt       3  10.375 ± 2.155  ops/ms
ClientGrpc.listUser                        thrpt       3   8.130 ± 1.760  ops/ms
ClientGrpc.createUser                       avgt       3   3.044 ± 0.950   ms/op
ClientGrpc.existUser                        avgt       3   2.915 ± 0.349   ms/op
ClientGrpc.getUser                          avgt       3   3.045 ± 0.444   ms/op
ClientGrpc.listUser                         avgt       3   3.894 ± 1.041   ms/op
ClientGrpc.createUser                     sample  313690   3.062 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.459           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.189           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.266           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.527           ms/op
ClientGrpc.existUser                      sample  327175   2.932 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.710           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.193           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.225           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.678           ms/op
ClientGrpc.getUser                        sample  315201   3.044 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.712           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.576           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.215           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.180           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.082           ms/op
ClientGrpc.listUser                       sample  239147   4.013 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.208           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.038           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.592           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.711           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.554           ms/op
