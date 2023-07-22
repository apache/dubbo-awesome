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
# Warmup Iteration   1: 4.239 ops/ms
# Warmup Iteration   2: 9.204 ops/ms
# Warmup Iteration   3: 10.099 ops/ms
Iteration   1: 10.621 ops/ms
Iteration   2: 10.512 ops/ms
Iteration   3: 10.662 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.599 ±(99.9%) 1.413 ops/ms [Average]
  (min, avg, max) = (10.512, 10.599, 10.662), stdev = 0.077
  CI (99.9%): [9.186, 12.011] (assumes normal distribution)


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
# Warmup Iteration   1: 7.684 ops/ms
# Warmup Iteration   2: 10.684 ops/ms
# Warmup Iteration   3: 11.037 ops/ms
Iteration   1: 11.231 ops/ms
Iteration   2: 11.192 ops/ms
Iteration   3: 11.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.146 ±(99.9%) 2.101 ops/ms [Average]
  (min, avg, max) = (11.015, 11.146, 11.231), stdev = 0.115
  CI (99.9%): [9.045, 13.247] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.530 ops/ms
# Warmup Iteration   2: 10.144 ops/ms
# Warmup Iteration   3: 10.497 ops/ms
Iteration   1: 10.545 ops/ms
Iteration   2: 10.517 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.560 ±(99.9%) 0.974 ops/ms [Average]
  (min, avg, max) = (10.517, 10.560, 10.620), stdev = 0.053
  CI (99.9%): [9.586, 11.535] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.388 ops/ms
# Warmup Iteration   2: 7.621 ops/ms
# Warmup Iteration   3: 8.055 ops/ms
Iteration   1: 7.994 ops/ms
Iteration   2: 8.265 ops/ms
Iteration   3: 8.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.116 ±(99.9%) 2.514 ops/ms [Average]
  (min, avg, max) = (7.994, 8.116, 8.265), stdev = 0.138
  CI (99.9%): [5.603, 10.630] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.608 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.003 ms/op
Iteration   1: 2.996 ±(99.9%) 0.004 ms/op
Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
Iteration   3: 3.025 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.030 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (2.996, 3.030, 3.070), stdev = 0.037
  CI (99.9%): [2.349, 3.711] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.957 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.003 ms/op
Iteration   1: 2.932 ±(99.9%) 0.004 ms/op
Iteration   2: 2.900 ±(99.9%) 0.004 ms/op
Iteration   3: 2.931 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.921 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (2.900, 2.921, 2.932), stdev = 0.018
  CI (99.9%): [2.589, 3.252] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.008 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.003 ms/op
Iteration   1: 3.018 ±(99.9%) 0.002 ms/op
Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
Iteration   3: 3.049 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.034 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (3.018, 3.034, 3.049), stdev = 0.015
  CI (99.9%): [2.755, 3.313] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.505 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.022 ms/op
Iteration   1: 3.998 ±(99.9%) 0.010 ms/op
Iteration   2: 3.944 ±(99.9%) 0.011 ms/op
Iteration   3: 3.908 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.950 ±(99.9%) 0.823 ms/op [Average]
  (min, avg, max) = (3.908, 3.950, 3.998), stdev = 0.045
  CI (99.9%): [3.128, 4.773] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.110 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.007 ms/op
Iteration   1: 3.014 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.536 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  8.776 ms/op
                 createUser·p0.9999: 18.494 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   2: 3.018 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.693 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.432 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.496 ms/op
                 createUser·p0.9999: 23.049 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 3.044 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.651 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  9.717 ms/op
                 createUser·p0.9999: 22.200 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317138
  mean =      3.025 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24923 
    [ 2.500,  5.000) = 290570 
    [ 5.000,  7.500) = 1254 
    [ 7.500, 10.000) = 128 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.929 ms/op
     p(99.9900) =     22.399 ms/op
     p(99.9990) =     23.385 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.851 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.630 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.545 ms/op
                 existUser·p0.9999: 11.919 ms/op
                 existUser·p1.00:   13.550 ms/op

Iteration   2: 2.919 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  5.926 ms/op
                 existUser·p0.9999: 19.726 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   3: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  6.827 ms/op
                 existUser·p0.9999: 15.168 ms/op
                 existUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327837
  mean =      2.928 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33626 
    [ 2.500,  5.000) = 293053 
    [ 5.000,  7.500) = 961 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.316 ms/op
     p(99.9900) =     16.915 ms/op
     p(99.9990) =     19.970 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.415 ms/op
                 getUser·p0.9999: 13.156 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.571 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  7.372 ms/op
                 getUser·p0.9999: 13.487 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.029 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316515
  mean =      3.034 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21342 
    [ 2.500,  5.000) = 293896 
    [ 5.000,  7.500) = 1022 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.571 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     16.696 ms/op
     p(99.9990) =     22.960 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


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
# Warmup Iteration   1: 5.279 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.071 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.010 ms/op
Iteration   1: 3.926 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.772 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  13.781 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 3.926 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.410 ms/op
                 listUser·p0.9999: 17.090 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.942 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 22.230 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244173
  mean =      3.931 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3784 
    [ 2.500,  5.000) = 220527 
    [ 5.000,  7.500) = 18652 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 251 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     14.071 ms/op
     p(99.9900) =     19.797 ms/op
     p(99.9990) =     22.734 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.599 ± 1.413  ops/ms
ClientGrpc.existUser                       thrpt       3  11.146 ± 2.101  ops/ms
ClientGrpc.getUser                         thrpt       3  10.560 ± 0.974  ops/ms
ClientGrpc.listUser                        thrpt       3   8.116 ± 2.514  ops/ms
ClientGrpc.createUser                       avgt       3   3.030 ± 0.681   ms/op
ClientGrpc.existUser                        avgt       3   2.921 ± 0.331   ms/op
ClientGrpc.getUser                          avgt       3   3.034 ± 0.279   ms/op
ClientGrpc.listUser                         avgt       3   3.950 ± 0.823   ms/op
ClientGrpc.createUser                     sample  317138   3.025 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.536           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.929           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.399           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.495           ms/op
ClientGrpc.existUser                      sample  327837   2.928 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.507           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.316           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.915           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.054           ms/op
ClientGrpc.getUser                        sample  316515   3.034 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.571           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.102           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.696           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.167           ms/op
ClientGrpc.listUser                       sample  244173   3.931 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.772           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.071           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.797           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.872           ms/op
