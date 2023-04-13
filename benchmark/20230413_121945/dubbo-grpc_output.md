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
# Warmup Iteration   1: 3.566 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 9.453 ops/ms
Iteration   1: 9.983 ops/ms
Iteration   2: 10.131 ops/ms
Iteration   3: 10.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.087 ±(99.9%) 1.658 ops/ms [Average]
  (min, avg, max) = (9.983, 10.087, 10.148), stdev = 0.091
  CI (99.9%): [8.429, 11.745] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.986 ops/ms
# Warmup Iteration   2: 9.932 ops/ms
# Warmup Iteration   3: 10.469 ops/ms
Iteration   1: 10.788 ops/ms
Iteration   2: 10.664 ops/ms
Iteration   3: 10.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.708 ±(99.9%) 1.272 ops/ms [Average]
  (min, avg, max) = (10.664, 10.708, 10.788), stdev = 0.070
  CI (99.9%): [9.437, 11.980] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.414 ops/ms
# Warmup Iteration   2: 9.461 ops/ms
# Warmup Iteration   3: 10.056 ops/ms
Iteration   1: 10.192 ops/ms
Iteration   2: 10.145 ops/ms
Iteration   3: 10.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.213 ±(99.9%) 1.447 ops/ms [Average]
  (min, avg, max) = (10.145, 10.213, 10.300), stdev = 0.079
  CI (99.9%): [8.765, 11.660] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.803 ops/ms
# Warmup Iteration   2: 7.197 ops/ms
# Warmup Iteration   3: 7.598 ops/ms
Iteration   1: 7.403 ops/ms
Iteration   2: 7.478 ops/ms
Iteration   3: 7.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.432 ±(99.9%) 0.738 ops/ms [Average]
  (min, avg, max) = (7.403, 7.432, 7.478), stdev = 0.040
  CI (99.9%): [6.693, 8.170] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.742 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.004 ms/op
Iteration   1: 3.222 ±(99.9%) 0.003 ms/op
Iteration   2: 3.193 ±(99.9%) 0.002 ms/op
Iteration   3: 3.241 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.219 ±(99.9%) 0.442 ms/op [Average]
  (min, avg, max) = (3.193, 3.219, 3.241), stdev = 0.024
  CI (99.9%): [2.777, 3.660] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.736 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.003 ms/op
Iteration   1: 3.034 ±(99.9%) 0.003 ms/op
Iteration   2: 3.147 ±(99.9%) 0.003 ms/op
Iteration   3: 3.101 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.094 ±(99.9%) 1.036 ms/op [Average]
  (min, avg, max) = (3.034, 3.094, 3.147), stdev = 0.057
  CI (99.9%): [2.058, 4.129] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.552 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.313 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.003 ms/op
Iteration   1: 3.181 ±(99.9%) 0.002 ms/op
Iteration   2: 3.155 ±(99.9%) 0.003 ms/op
Iteration   3: 3.130 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.155 ±(99.9%) 0.468 ms/op [Average]
  (min, avg, max) = (3.130, 3.155, 3.181), stdev = 0.026
  CI (99.9%): [2.688, 3.623] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.717 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.292 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.029 ms/op
Iteration   1: 4.165 ±(99.9%) 0.015 ms/op
Iteration   2: 4.155 ±(99.9%) 0.014 ms/op
Iteration   3: 4.173 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.164 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (4.155, 4.164, 4.173), stdev = 0.009
  CI (99.9%): [3.999, 4.330] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.669 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.369 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.009 ms/op
Iteration   1: 3.234 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  9.521 ms/op
                 createUser·p0.9999: 14.229 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  10.568 ms/op
                 createUser·p0.9999: 17.199 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  8.009 ms/op
                 createUser·p0.9999: 17.695 ms/op
                 createUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302247
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 521 
    [ 1.250,  2.500) = 15298 
    [ 2.500,  3.750) = 256062 
    [ 3.750,  5.000) = 26230 
    [ 5.000,  6.250) = 2486 
    [ 6.250,  7.500) = 895 
    [ 7.500,  8.750) = 402 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.349 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     19.264 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.391 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  7.870 ms/op
                 existUser·p0.9999: 29.564 ms/op
                 existUser·p1.00:   31.588 ms/op

Iteration   2: 2.983 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.528 ms/op
                 existUser·p0.9999: 26.930 ms/op
                 existUser·p1.00:   27.820 ms/op

Iteration   3: 2.969 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.636 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.907 ms/op
                 existUser·p0.999:  10.266 ms/op
                 existUser·p0.9999: 21.970 ms/op
                 existUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322556
  mean =      2.975 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36634 
    [ 2.500,  5.000) = 283647 
    [ 5.000,  7.500) = 1829 
    [ 7.500, 10.000) = 152 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 38 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      9.304 ms/op
     p(99.9900) =     28.259 ms/op
     p(99.9990) =     29.902 ms/op
     p(99.9999) =     31.588 ms/op
    p(100.0000) =     31.588 ms/op


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
# Warmup Iteration   1: 4.434 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.007 ms/op
Iteration   1: 3.145 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.602 ms/op
                 getUser·p0.9999: 14.183 ms/op
                 getUser·p1.00:   14.467 ms/op

Iteration   2: 3.082 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  7.635 ms/op
                 getUser·p0.9999: 22.630 ms/op
                 getUser·p1.00:   22.872 ms/op

Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  10.224 ms/op
                 getUser·p0.9999: 18.022 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309188
  mean =      3.105 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15295 
    [ 2.500,  5.000) = 291639 
    [ 5.000,  7.500) = 1803 
    [ 7.500, 10.000) = 236 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      8.225 ms/op
     p(99.9900) =     21.862 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 4.978 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.243 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.012 ms/op
Iteration   1: 4.036 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  13.116 ms/op
                 listUser·p0.9999: 20.161 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 4.050 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   7.256 ms/op
                 listUser·p0.999:  16.547 ms/op
                 listUser·p0.9999: 19.435 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 3.833 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  15.861 ms/op
                 listUser·p0.9999: 23.614 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241834
  mean =      3.971 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3419 
    [ 2.500,  5.000) = 215408 
    [ 5.000,  7.500) = 21294 
    [ 7.500, 10.000) = 1265 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     15.420 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     23.945 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.087 ± 1.658  ops/ms
ClientGrpc.existUser                       thrpt       3  10.708 ± 1.272  ops/ms
ClientGrpc.getUser                         thrpt       3  10.213 ± 1.447  ops/ms
ClientGrpc.listUser                        thrpt       3   7.432 ± 0.738  ops/ms
ClientGrpc.createUser                       avgt       3   3.219 ± 0.442   ms/op
ClientGrpc.existUser                        avgt       3   3.094 ± 1.036   ms/op
ClientGrpc.getUser                          avgt       3   3.155 ± 0.468   ms/op
ClientGrpc.listUser                         avgt       3   4.164 ± 0.165   ms/op
ClientGrpc.createUser                     sample  302247   3.174 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.611           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.349           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.355           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.531           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.726           ms/op
ClientGrpc.existUser                      sample  322556   2.975 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.636           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.719           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.304           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.259           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.588           ms/op
ClientGrpc.getUser                        sample  309188   3.105 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.643           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.225           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.862           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.872           ms/op
ClientGrpc.listUser                       sample  241834   3.971 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.962           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.420           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.791           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
