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
# Warmup Iteration   1: 3.951 ops/ms
# Warmup Iteration   2: 8.941 ops/ms
# Warmup Iteration   3: 10.129 ops/ms
Iteration   1: 10.122 ops/ms
Iteration   2: 9.937 ops/ms
Iteration   3: 9.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.973 ±(99.9%) 2.452 ops/ms [Average]
  (min, avg, max) = (9.860, 9.973, 10.122), stdev = 0.134
  CI (99.9%): [7.520, 12.425] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.462 ops/ms
# Warmup Iteration   2: 10.583 ops/ms
# Warmup Iteration   3: 10.173 ops/ms
Iteration   1: 10.528 ops/ms
Iteration   2: 10.700 ops/ms
Iteration   3: 10.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.610 ±(99.9%) 1.576 ops/ms [Average]
  (min, avg, max) = (10.528, 10.610, 10.700), stdev = 0.086
  CI (99.9%): [9.034, 12.186] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.585 ops/ms
# Warmup Iteration   2: 9.872 ops/ms
# Warmup Iteration   3: 9.856 ops/ms
Iteration   1: 10.072 ops/ms
Iteration   2: 10.087 ops/ms
Iteration   3: 10.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.072 ±(99.9%) 0.288 ops/ms [Average]
  (min, avg, max) = (10.056, 10.072, 10.087), stdev = 0.016
  CI (99.9%): [9.783, 10.360] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.208 ops/ms
# Warmup Iteration   2: 7.492 ops/ms
# Warmup Iteration   3: 7.864 ops/ms
Iteration   1: 7.913 ops/ms
Iteration   2: 8.052 ops/ms
Iteration   3: 8.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.990 ±(99.9%) 1.295 ops/ms [Average]
  (min, avg, max) = (7.913, 7.990, 8.052), stdev = 0.071
  CI (99.9%): [6.696, 9.285] (assumes normal distribution)


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
# Warmup Iteration   1: 4.238 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.001 ms/op
Iteration   1: 3.256 ±(99.9%) 0.002 ms/op
Iteration   2: 3.248 ±(99.9%) 0.002 ms/op
Iteration   3: 3.228 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.244 ±(99.9%) 0.268 ms/op [Average]
  (min, avg, max) = (3.228, 3.244, 3.256), stdev = 0.015
  CI (99.9%): [2.976, 3.513] (assumes normal distribution)


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
# Warmup Iteration   1: 4.016 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.002 ms/op
Iteration   1: 3.117 ±(99.9%) 0.002 ms/op
Iteration   2: 3.089 ±(99.9%) 0.002 ms/op
Iteration   3: 3.045 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.084 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (3.045, 3.084, 3.117), stdev = 0.036
  CI (99.9%): [2.423, 3.744] (assumes normal distribution)


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
# Warmup Iteration   1: 4.381 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.336 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.257 ±(99.9%) 0.026 ms/op
Iteration   1: 3.247 ±(99.9%) 0.003 ms/op
Iteration   2: 3.219 ±(99.9%) 0.002 ms/op
Iteration   3: 3.222 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.229 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (3.219, 3.229, 3.247), stdev = 0.015
  CI (99.9%): [2.952, 3.506] (assumes normal distribution)


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
# Warmup Iteration   1: 5.212 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.349 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.180 ±(99.9%) 0.018 ms/op
Iteration   1: 3.970 ±(99.9%) 0.035 ms/op
Iteration   2: 4.005 ±(99.9%) 0.014 ms/op
Iteration   3: 3.956 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.977 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (3.956, 3.977, 4.005), stdev = 0.025
  CI (99.9%): [3.521, 4.433] (assumes normal distribution)


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.007 ms/op
Iteration   1: 3.232 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.841 ms/op
                 createUser·p0.9999: 16.788 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   2: 3.233 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.992 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.125 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  7.242 ms/op
                 createUser·p0.9999: 14.389 ms/op
                 createUser·p1.00:   15.679 ms/op

Iteration   3: 3.306 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   4.002 ms/op
                 createUser·p0.95:   4.190 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  12.478 ms/op
                 createUser·p0.9999: 26.258 ms/op
                 createUser·p1.00:   26.608 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 294625
  mean =      3.257 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18708 
    [ 2.500,  5.000) = 274846 
    [ 5.000,  7.500) = 673 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.965 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =     10.263 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     26.513 ms/op
     p(99.9999) =     26.608 ms/op
    p(100.0000) =     26.608 ms/op


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
Iteration   1: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  5.749 ms/op
                 existUser·p0.9999: 18.978 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   2: 3.128 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  7.734 ms/op
                 existUser·p0.9999: 18.055 ms/op
                 existUser·p1.00:   18.481 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  7.429 ms/op
                 existUser·p0.9999: 19.661 ms/op
                 existUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311257
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1503 
    [ 1.250,  2.500) = 34248 
    [ 2.500,  3.750) = 240965 
    [ 3.750,  5.000) = 33547 
    [ 5.000,  6.250) = 498 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 54 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.274 ms/op
     p(99.9900) =     19.100 ms/op
     p(99.9990) =     19.817 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 4.593 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.007 ms/op
Iteration   1: 3.301 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  6.463 ms/op
                 getUser·p0.9999: 17.331 ms/op
                 getUser·p1.00:   17.793 ms/op

Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.077 ms/op
                 getUser·p0.9999: 21.934 ms/op
                 getUser·p1.00:   22.315 ms/op

Iteration   3: 3.218 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.912 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  8.425 ms/op
                 getUser·p0.9999: 21.496 ms/op
                 getUser·p1.00:   22.446 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 295128
  mean =      3.253 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12536 
    [ 2.500,  5.000) = 281451 
    [ 5.000,  7.500) = 859 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.395 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     22.318 ms/op
     p(99.9999) =     22.446 ms/op
    p(100.0000) =     22.446 ms/op


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
# Warmup Iteration   1: 5.294 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.193 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.028 ±(99.9%) 0.013 ms/op
Iteration   1: 4.041 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.041 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  14.809 ms/op
                 listUser·p0.9999: 21.802 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   2: 4.131 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.222 ms/op
                 listUser·p0.9999: 27.075 ms/op
                 listUser·p1.00:   27.558 ms/op

Iteration   3: 4.024 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.872 ms/op
                 listUser·p0.9999: 30.049 ms/op
                 listUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236225
  mean =      4.065 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2871 
    [ 2.500,  5.000) = 201155 
    [ 5.000,  7.500) = 30958 
    [ 7.500, 10.000) = 853 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.041 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.915 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     15.725 ms/op
     p(99.9900) =     27.719 ms/op
     p(99.9990) =     30.308 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.973 ± 2.452  ops/ms
ClientGrpc.existUser                       thrpt       3  10.610 ± 1.576  ops/ms
ClientGrpc.getUser                         thrpt       3  10.072 ± 0.288  ops/ms
ClientGrpc.listUser                        thrpt       3   7.990 ± 1.295  ops/ms
ClientGrpc.createUser                       avgt       3   3.244 ± 0.268   ms/op
ClientGrpc.existUser                        avgt       3   3.084 ± 0.661   ms/op
ClientGrpc.getUser                          avgt       3   3.229 ± 0.277   ms/op
ClientGrpc.listUser                         avgt       3   3.977 ± 0.456   ms/op
ClientGrpc.createUser                     sample  294625   3.257 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.824           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.232           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.965           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.263           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.854           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.608           ms/op
ClientGrpc.existUser                      sample  311257   3.084 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.639           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.068           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.969           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.274           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.100           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.988           ms/op
ClientGrpc.getUser                        sample  295128   3.253 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.598           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.219           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.125           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.395           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.725           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.446           ms/op
ClientGrpc.listUser                       sample  236225   4.065 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.041           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.915           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.988           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.725           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.719           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.376           ms/op
