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
# Warmup Iteration   1: 4.129 ops/ms
# Warmup Iteration   2: 8.744 ops/ms
# Warmup Iteration   3: 9.859 ops/ms
Iteration   1: 10.308 ops/ms
Iteration   2: 10.176 ops/ms
Iteration   3: 10.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.270 ±(99.9%) 1.494 ops/ms [Average]
  (min, avg, max) = (10.176, 10.270, 10.327), stdev = 0.082
  CI (99.9%): [8.776, 11.764] (assumes normal distribution)


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
# Warmup Iteration   1: 7.301 ops/ms
# Warmup Iteration   2: 10.151 ops/ms
# Warmup Iteration   3: 10.613 ops/ms
Iteration   1: 10.469 ops/ms
Iteration   2: 10.800 ops/ms
Iteration   3: 10.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.702 ±(99.9%) 3.693 ops/ms [Average]
  (min, avg, max) = (10.469, 10.702, 10.837), stdev = 0.202
  CI (99.9%): [7.009, 14.395] (assumes normal distribution)


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
# Warmup Iteration   1: 6.184 ops/ms
# Warmup Iteration   2: 9.894 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.316 ops/ms
Iteration   2: 10.190 ops/ms
Iteration   3: 10.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.242 ±(99.9%) 1.199 ops/ms [Average]
  (min, avg, max) = (10.190, 10.242, 10.316), stdev = 0.066
  CI (99.9%): [9.043, 11.442] (assumes normal distribution)


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
# Warmup Iteration   1: 5.277 ops/ms
# Warmup Iteration   2: 7.831 ops/ms
# Warmup Iteration   3: 7.979 ops/ms
Iteration   1: 8.091 ops/ms
Iteration   2: 8.157 ops/ms
Iteration   3: 8.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.160 ±(99.9%) 1.296 ops/ms [Average]
  (min, avg, max) = (8.091, 8.160, 8.232), stdev = 0.071
  CI (99.9%): [6.864, 9.456] (assumes normal distribution)


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
# Warmup Iteration   1: 4.510 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.001 ms/op
Iteration   1: 3.137 ±(99.9%) 0.005 ms/op
Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
Iteration   3: 3.138 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.139 ±(99.9%) 0.065 ms/op [Average]
  (min, avg, max) = (3.137, 3.139, 3.143), stdev = 0.004
  CI (99.9%): [3.074, 3.205] (assumes normal distribution)


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
# Warmup Iteration   1: 4.307 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.001 ms/op
Iteration   1: 3.026 ±(99.9%) 0.002 ms/op
Iteration   2: 3.011 ±(99.9%) 0.001 ms/op
Iteration   3: 3.057 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.031 ±(99.9%) 0.423 ms/op [Average]
  (min, avg, max) = (3.011, 3.031, 3.057), stdev = 0.023
  CI (99.9%): [2.608, 3.455] (assumes normal distribution)


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.002 ms/op
Iteration   1: 3.130 ±(99.9%) 0.003 ms/op
Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
Iteration   3: 3.093 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.110 ±(99.9%) 0.343 ms/op [Average]
  (min, avg, max) = (3.093, 3.110, 3.130), stdev = 0.019
  CI (99.9%): [2.766, 3.453] (assumes normal distribution)


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
# Warmup Iteration   1: 5.675 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.027 ms/op
Iteration   1: 3.903 ±(99.9%) 0.016 ms/op
Iteration   2: 3.971 ±(99.9%) 0.010 ms/op
Iteration   3: 3.887 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.920 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.887, 3.920, 3.971), stdev = 0.044
  CI (99.9%): [3.109, 4.732] (assumes normal distribution)


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
# Warmup Iteration   1: 4.479 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.309 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.006 ms/op
Iteration   1: 3.115 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  8.654 ms/op
                 createUser·p0.9999: 17.906 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   2: 3.136 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  8.292 ms/op
                 createUser·p0.9999: 17.754 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   3: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  9.880 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309024
  mean =      3.107 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 170 
    [ 1.250,  2.500) = 10016 
    [ 2.500,  3.750) = 281995 
    [ 3.750,  5.000) = 15095 
    [ 5.000,  6.250) = 783 
    [ 6.250,  7.500) = 445 
    [ 7.500,  8.750) = 218 
    [ 8.750, 10.000) = 83 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 75 
    [17.500, 18.750) = 63 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.667 ms/op
     p(99.9900) =     18.088 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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
# Warmup Iteration   1: 4.094 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.005 ms/op
Iteration   1: 2.953 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.345 ms/op
                 existUser·p0.999:  7.246 ms/op
                 existUser·p0.9999: 13.083 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   2: 2.965 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.563 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  6.291 ms/op
                 existUser·p0.9999: 13.728 ms/op
                 existUser·p1.00:   14.320 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  7.683 ms/op
                 existUser·p0.9999: 16.705 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323158
  mean =      2.968 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1793 
    [ 1.250,  2.500) = 25907 
    [ 2.500,  3.750) = 283536 
    [ 3.750,  5.000) = 10389 
    [ 5.000,  6.250) = 913 
    [ 6.250,  7.500) = 398 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.127 ms/op
     p(99.9900) =     16.456 ms/op
     p(99.9990) =     16.868 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.006 ms/op
Iteration   1: 3.180 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.431 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.073 ms/op
                 getUser·p0.9999: 12.285 ms/op
                 getUser·p1.00:   12.632 ms/op

Iteration   2: 3.124 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  7.450 ms/op
                 getUser·p0.9999: 13.173 ms/op
                 getUser·p1.00:   13.386 ms/op

Iteration   3: 3.165 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.935 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.701 ms/op
                 getUser·p0.9999: 16.908 ms/op
                 getUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 304131
  mean =      3.156 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 4693 
    [ 2.500,  3.750) = 276615 
    [ 3.750,  5.000) = 21221 
    [ 5.000,  6.250) = 839 
    [ 6.250,  7.500) = 402 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.175 ms/op
     p(99.9900) =     16.328 ms/op
     p(99.9990) =     17.168 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 5.301 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.031 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.009 ms/op
Iteration   1: 3.961 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.311 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  12.943 ms/op
                 listUser·p0.9999: 15.363 ms/op
                 listUser·p1.00:   15.630 ms/op

Iteration   2: 3.984 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   6.766 ms/op
                 listUser·p0.999:  13.763 ms/op
                 listUser·p0.9999: 16.185 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.973 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  14.934 ms/op
                 listUser·p0.9999: 19.038 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241648
  mean =      3.973 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 2416 
    [ 2.500,  3.750) = 85538 
    [ 3.750,  5.000) = 137988 
    [ 5.000,  6.250) = 9609 
    [ 6.250,  7.500) = 5157 
    [ 7.500,  8.750) = 403 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 120 
    [15.000, 16.250) = 57 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.096 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.477 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     13.686 ms/op
     p(99.9900) =     18.498 ms/op
     p(99.9990) =     19.156 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.270 ± 1.494  ops/ms
ClientGrpc.existUser                       thrpt       3  10.702 ± 3.693  ops/ms
ClientGrpc.getUser                         thrpt       3  10.242 ± 1.199  ops/ms
ClientGrpc.listUser                        thrpt       3   8.160 ± 1.296  ops/ms
ClientGrpc.createUser                       avgt       3   3.139 ± 0.065   ms/op
ClientGrpc.existUser                        avgt       3   3.031 ± 0.423   ms/op
ClientGrpc.getUser                          avgt       3   3.110 ± 0.343   ms/op
ClientGrpc.listUser                         avgt       3   3.920 ± 0.811   ms/op
ClientGrpc.createUser                     sample  309024   3.107 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.691           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.600           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.667           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.088           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.464           ms/op
ClientGrpc.existUser                      sample  323158   2.968 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.563           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.127           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.456           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.974           ms/op
ClientGrpc.getUser                        sample  304131   3.156 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.431           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.113           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.175           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.328           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.302           ms/op
ClientGrpc.listUser                       sample  241648   3.973 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.096           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.477           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.686           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.498           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.268           ms/op
