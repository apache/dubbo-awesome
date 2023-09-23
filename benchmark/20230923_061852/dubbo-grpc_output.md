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
# Warmup Iteration   1: 4.788 ops/ms
# Warmup Iteration   2: 8.971 ops/ms
# Warmup Iteration   3: 9.828 ops/ms
Iteration   1: 10.271 ops/ms
Iteration   2: 10.440 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.422 ±(99.9%) 2.596 ops/ms [Average]
  (min, avg, max) = (10.271, 10.422, 10.554), stdev = 0.142
  CI (99.9%): [7.825, 13.018] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.211 ops/ms
# Warmup Iteration   2: 10.526 ops/ms
# Warmup Iteration   3: 10.986 ops/ms
Iteration   1: 10.580 ops/ms
Iteration   2: 10.497 ops/ms
Iteration   3: 10.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.680 ±(99.9%) 4.541 ops/ms [Average]
  (min, avg, max) = (10.497, 10.680, 10.963), stdev = 0.249
  CI (99.9%): [6.139, 15.220] (assumes normal distribution)


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
# Warmup Iteration   1: 7.336 ops/ms
# Warmup Iteration   2: 10.076 ops/ms
# Warmup Iteration   3: 10.294 ops/ms
Iteration   1: 10.685 ops/ms
Iteration   2: 10.407 ops/ms
Iteration   3: 10.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.460 ±(99.9%) 3.724 ops/ms [Average]
  (min, avg, max) = (10.287, 10.460, 10.685), stdev = 0.204
  CI (99.9%): [6.736, 14.183] (assumes normal distribution)


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
# Warmup Iteration   1: 6.970 ops/ms
# Warmup Iteration   2: 8.001 ops/ms
# Warmup Iteration   3: 8.102 ops/ms
Iteration   1: 8.066 ops/ms
Iteration   2: 8.371 ops/ms
Iteration   3: 8.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.178 ±(99.9%) 3.053 ops/ms [Average]
  (min, avg, max) = (8.066, 8.178, 8.371), stdev = 0.167
  CI (99.9%): [5.125, 11.231] (assumes normal distribution)


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
# Warmup Iteration   1: 3.858 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.002 ms/op
Iteration   1: 3.116 ±(99.9%) 0.002 ms/op
Iteration   2: 3.119 ±(99.9%) 0.002 ms/op
Iteration   3: 3.105 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.113 ±(99.9%) 0.125 ms/op [Average]
  (min, avg, max) = (3.105, 3.113, 3.119), stdev = 0.007
  CI (99.9%): [2.988, 3.238] (assumes normal distribution)


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
# Warmup Iteration   1: 3.852 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.002 ms/op
Iteration   1: 2.945 ±(99.9%) 0.002 ms/op
Iteration   2: 2.923 ±(99.9%) 0.002 ms/op
Iteration   3: 2.994 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.954 ±(99.9%) 0.667 ms/op [Average]
  (min, avg, max) = (2.923, 2.954, 2.994), stdev = 0.037
  CI (99.9%): [2.287, 3.621] (assumes normal distribution)


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.002 ms/op
Iteration   1: 3.111 ±(99.9%) 0.002 ms/op
Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
Iteration   3: 3.053 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.100 ±(99.9%) 0.767 ms/op [Average]
  (min, avg, max) = (3.053, 3.100, 3.135), stdev = 0.042
  CI (99.9%): [2.333, 3.867] (assumes normal distribution)


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
# Warmup Iteration   1: 4.760 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.031 ms/op
Iteration   1: 3.867 ±(99.9%) 0.018 ms/op
Iteration   2: 3.857 ±(99.9%) 0.020 ms/op
Iteration   3: 3.897 ±(99.9%) 0.060 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.874 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.857, 3.874, 3.897), stdev = 0.021
  CI (99.9%): [3.491, 4.257] (assumes normal distribution)


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
# Warmup Iteration   1: 4.018 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
Iteration   1: 3.100 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.482 ms/op
                 createUser·p0.999:  9.999 ms/op
                 createUser·p0.9999: 11.447 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   2: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.353 ms/op
                 createUser·p0.9999: 16.155 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.629 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.137 ms/op
                 createUser·p0.999:  11.550 ms/op
                 createUser·p0.9999: 16.846 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312625
  mean =      3.070 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 859 
    [ 1.250,  2.500) = 16259 
    [ 2.500,  3.750) = 277348 
    [ 3.750,  5.000) = 16658 
    [ 5.000,  6.250) = 699 
    [ 6.250,  7.500) = 340 
    [ 7.500,  8.750) = 82 
    [ 8.750, 10.000) = 76 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      9.837 ms/op
     p(99.9900) =     16.249 ms/op
     p(99.9990) =     18.055 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 2.968 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.293 ms/op
                 existUser·p0.9999: 11.935 ms/op
                 existUser·p1.00:   12.222 ms/op

Iteration   2: 2.911 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.620 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.565 ms/op
                 existUser·p0.9999: 13.960 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  9.663 ms/op
                 existUser·p0.9999: 21.004 ms/op
                 existUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324196
  mean =      2.959 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29599 
    [ 2.500,  5.000) = 292897 
    [ 5.000,  7.500) = 1237 
    [ 7.500, 10.000) = 274 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.729 ms/op
     p(99.9900) =     17.116 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.187 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
Iteration   1: 3.137 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.805 ms/op
                 getUser·p0.9999: 13.710 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 3.151 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  8.114 ms/op
                 getUser·p0.9999: 15.604 ms/op
                 getUser·p1.00:   16.368 ms/op

Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.572 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.959 ms/op
                 getUser·p0.9999: 16.319 ms/op
                 getUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306771
  mean =      3.129 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 767 
    [ 1.250,  2.500) = 7534 
    [ 2.500,  3.750) = 274521 
    [ 3.750,  5.000) = 22458 
    [ 5.000,  6.250) = 843 
    [ 6.250,  7.500) = 280 
    [ 7.500,  8.750) = 80 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 65 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.179 ms/op
     p(99.9900) =     15.996 ms/op
     p(99.9990) =     16.577 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 4.685 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.895 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.010 ms/op
Iteration   1: 3.902 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  12.106 ms/op
                 listUser·p0.9999: 13.530 ms/op
                 listUser·p1.00:   14.025 ms/op

Iteration   2: 3.854 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  12.878 ms/op
                 listUser·p0.9999: 15.227 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   3: 3.848 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  14.154 ms/op
                 listUser·p0.9999: 18.373 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248214
  mean =      3.868 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 4177 
    [ 2.500,  3.750) = 113397 
    [ 3.750,  5.000) = 114649 
    [ 5.000,  6.250) = 11037 
    [ 6.250,  7.500) = 3934 
    [ 7.500,  8.750) = 369 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 180 
    [12.500, 13.750) = 180 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     12.747 ms/op
     p(99.9900) =     16.505 ms/op
     p(99.9990) =     18.596 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.422 ± 2.596  ops/ms
ClientGrpc.existUser                       thrpt       3  10.680 ± 4.541  ops/ms
ClientGrpc.getUser                         thrpt       3  10.460 ± 3.724  ops/ms
ClientGrpc.listUser                        thrpt       3   8.178 ± 3.053  ops/ms
ClientGrpc.createUser                       avgt       3   3.113 ± 0.125   ms/op
ClientGrpc.existUser                        avgt       3   2.954 ± 0.667   ms/op
ClientGrpc.getUser                          avgt       3   3.100 ± 0.767   ms/op
ClientGrpc.listUser                         avgt       3   3.874 ± 0.383   ms/op
ClientGrpc.createUser                     sample  312625   3.070 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.629           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.035           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.837           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.249           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.055           ms/op
ClientGrpc.existUser                      sample  324196   2.959 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.620           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.707           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.729           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.116           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.037           ms/op
ClientGrpc.getUser                        sample  306771   3.129 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.572           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.179           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.996           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.498           ms/op
ClientGrpc.listUser                       sample  248214   3.868 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.098           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.448           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          12.747           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.505           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.612           ms/op
