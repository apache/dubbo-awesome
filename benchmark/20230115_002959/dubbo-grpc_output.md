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
# Warmup Iteration   1: 4.877 ops/ms
# Warmup Iteration   2: 9.801 ops/ms
# Warmup Iteration   3: 10.620 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.799 ops/ms
Iteration   3: 10.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.588 ±(99.9%) 3.884 ops/ms [Average]
  (min, avg, max) = (10.373, 10.588, 10.799), stdev = 0.213
  CI (99.9%): [6.703, 14.472] (assumes normal distribution)


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
# Warmup Iteration   1: 8.421 ops/ms
# Warmup Iteration   2: 10.576 ops/ms
# Warmup Iteration   3: 11.133 ops/ms
Iteration   1: 10.853 ops/ms
Iteration   2: 10.781 ops/ms
Iteration   3: 11.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.965 ±(99.9%) 4.706 ops/ms [Average]
  (min, avg, max) = (10.781, 10.965, 11.260), stdev = 0.258
  CI (99.9%): [6.259, 15.671] (assumes normal distribution)


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
# Warmup Iteration   1: 7.189 ops/ms
# Warmup Iteration   2: 10.518 ops/ms
# Warmup Iteration   3: 10.811 ops/ms
Iteration   1: 10.413 ops/ms
Iteration   2: 10.494 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.535 ±(99.9%) 2.676 ops/ms [Average]
  (min, avg, max) = (10.413, 10.535, 10.698), stdev = 0.147
  CI (99.9%): [7.859, 13.211] (assumes normal distribution)


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
# Warmup Iteration   1: 6.271 ops/ms
# Warmup Iteration   2: 7.827 ops/ms
# Warmup Iteration   3: 8.149 ops/ms
Iteration   1: 8.356 ops/ms
Iteration   2: 8.168 ops/ms
Iteration   3: 8.116 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.213 ±(99.9%) 2.303 ops/ms [Average]
  (min, avg, max) = (8.116, 8.213, 8.356), stdev = 0.126
  CI (99.9%): [5.910, 10.516] (assumes normal distribution)


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
# Warmup Iteration   1: 3.928 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.001 ms/op
Iteration   1: 3.137 ±(99.9%) 0.003 ms/op
Iteration   2: 2.943 ±(99.9%) 0.004 ms/op
Iteration   3: 2.967 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 1.934 ms/op [Average]
  (min, avg, max) = (2.943, 3.016, 3.137), stdev = 0.106
  CI (99.9%): [1.081, 4.950] (assumes normal distribution)


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.003 ms/op
Iteration   1: 2.890 ±(99.9%) 0.003 ms/op
Iteration   2: 2.971 ±(99.9%) 0.002 ms/op
Iteration   3: 2.881 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.914 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (2.881, 2.914, 2.971), stdev = 0.050
  CI (99.9%): [2.003, 3.825] (assumes normal distribution)


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
# Warmup Iteration   1: 3.912 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.007 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.003 ms/op
Iteration   1: 3.033 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 3.000 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.020 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (3.000, 3.020, 3.033), stdev = 0.017
  CI (99.9%): [2.702, 3.337] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.021 ms/op
Iteration   1: 3.863 ±(99.9%) 0.020 ms/op
Iteration   2: 3.943 ±(99.9%) 0.049 ms/op
Iteration   3: 3.956 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.920 ±(99.9%) 0.918 ms/op [Average]
  (min, avg, max) = (3.863, 3.920, 3.956), stdev = 0.050
  CI (99.9%): [3.002, 4.839] (assumes normal distribution)


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
# Warmup Iteration   1: 3.528 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.333 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.665 ms/op
                 createUser·p0.9999: 11.908 ms/op
                 createUser·p1.00:   12.272 ms/op

Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  6.718 ms/op
                 createUser·p0.9999: 21.168 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   3: 3.139 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  6.603 ms/op
                 createUser·p0.9999: 14.667 ms/op
                 createUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304941
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26461 
    [ 2.500,  5.000) = 277588 
    [ 5.000,  7.500) = 633 
    [ 7.500, 10.000) = 48 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.333 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.029 ms/op
     p(99.9900) =     19.926 ms/op
     p(99.9990) =     21.560 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.357 ms/op
                 existUser·p0.9999: 11.683 ms/op
                 existUser·p1.00:   12.321 ms/op

Iteration   2: 2.905 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.018 ms/op
                 existUser·p0.999:  5.591 ms/op
                 existUser·p0.9999: 19.365 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.696 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  9.038 ms/op
                 existUser·p0.9999: 14.406 ms/op
                 existUser·p1.00:   14.713 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325218
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2367 
    [ 1.250,  2.500) = 45760 
    [ 2.500,  3.750) = 260120 
    [ 3.750,  5.000) = 16137 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 122 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      6.568 ms/op
     p(99.9900) =     16.593 ms/op
     p(99.9990) =     19.489 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 3.578 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.006 ms/op
Iteration   1: 3.016 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  7.208 ms/op
                 getUser·p0.9999: 13.995 ms/op
                 getUser·p1.00:   14.729 ms/op

Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.637 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.030 ms/op
                 getUser·p0.9999: 16.008 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.874 ms/op
                 getUser·p0.9999: 18.595 ms/op
                 getUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312592
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1393 
    [ 1.250,  2.500) = 30559 
    [ 2.500,  3.750) = 249584 
    [ 3.750,  5.000) = 30306 
    [ 5.000,  6.250) = 357 
    [ 6.250,  7.500) = 143 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.637 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.676 ms/op
     p(99.9900) =     16.900 ms/op
     p(99.9990) =     18.870 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 4.700 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.012 ms/op
Iteration   1: 4.024 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  14.425 ms/op
                 listUser·p0.9999: 16.910 ms/op
                 listUser·p1.00:   17.957 ms/op

Iteration   2: 3.996 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.746 ms/op
                 listUser·p0.999:  15.279 ms/op
                 listUser·p0.9999: 21.363 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 4.019 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  15.144 ms/op
                 listUser·p0.9999: 30.385 ms/op
                 listUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239218
  mean =      4.013 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4245 
    [ 2.500,  5.000) = 206657 
    [ 5.000,  7.500) = 27282 
    [ 7.500, 10.000) = 590 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.846 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     14.795 ms/op
     p(99.9900) =     27.858 ms/op
     p(99.9990) =     30.736 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.588 ± 3.884  ops/ms
ClientGrpc.existUser                       thrpt       3  10.965 ± 4.706  ops/ms
ClientGrpc.getUser                         thrpt       3  10.535 ± 2.676  ops/ms
ClientGrpc.listUser                        thrpt       3   8.213 ± 2.303  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 1.934   ms/op
ClientGrpc.existUser                        avgt       3   2.914 ± 0.911   ms/op
ClientGrpc.getUser                          avgt       3   3.020 ± 0.317   ms/op
ClientGrpc.listUser                         avgt       3   3.920 ± 0.918   ms/op
ClientGrpc.createUser                     sample  304941   3.148 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.333           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.842           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.994           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.029           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.926           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.692           ms/op
ClientGrpc.existUser                      sample  325218   2.952 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.693           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.568           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.593           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.530           ms/op
ClientGrpc.getUser                        sample  312592   3.070 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.637           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.676           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.900           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.005           ms/op
ClientGrpc.listUser                       sample  239218   4.013 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.896           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.846           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.120           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.795           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.858           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.736           ms/op
