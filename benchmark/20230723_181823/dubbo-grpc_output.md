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
# Warmup Iteration   1: 3.705 ops/ms
# Warmup Iteration   2: 7.566 ops/ms
# Warmup Iteration   3: 8.944 ops/ms
Iteration   1: 9.483 ops/ms
Iteration   2: 9.295 ops/ms
Iteration   3: 9.630 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.469 ±(99.9%) 3.058 ops/ms [Average]
  (min, avg, max) = (9.295, 9.469, 9.630), stdev = 0.168
  CI (99.9%): [6.411, 12.528] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.445 ops/ms
# Warmup Iteration   2: 9.344 ops/ms
# Warmup Iteration   3: 9.829 ops/ms
Iteration   1: 9.992 ops/ms
Iteration   2: 9.945 ops/ms
Iteration   3: 10.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.031 ±(99.9%) 2.025 ops/ms [Average]
  (min, avg, max) = (9.945, 10.031, 10.157), stdev = 0.111
  CI (99.9%): [8.006, 12.057] (assumes normal distribution)


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
# Warmup Iteration   1: 5.792 ops/ms
# Warmup Iteration   2: 8.649 ops/ms
# Warmup Iteration   3: 9.155 ops/ms
Iteration   1: 9.521 ops/ms
Iteration   2: 9.495 ops/ms
Iteration   3: 9.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.524 ±(99.9%) 0.554 ops/ms [Average]
  (min, avg, max) = (9.495, 9.524, 9.556), stdev = 0.030
  CI (99.9%): [8.970, 10.078] (assumes normal distribution)


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
# Warmup Iteration   1: 4.711 ops/ms
# Warmup Iteration   2: 6.922 ops/ms
# Warmup Iteration   3: 6.936 ops/ms
Iteration   1: 7.176 ops/ms
Iteration   2: 7.231 ops/ms
Iteration   3: 7.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.166 ±(99.9%) 1.290 ops/ms [Average]
  (min, avg, max) = (7.090, 7.166, 7.231), stdev = 0.071
  CI (99.9%): [5.875, 8.456] (assumes normal distribution)


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
# Warmup Iteration   1: 4.983 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.005 ms/op
Iteration   1: 3.341 ±(99.9%) 0.004 ms/op
Iteration   2: 3.467 ±(99.9%) 0.004 ms/op
Iteration   3: 3.405 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.404 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (3.341, 3.404, 3.467), stdev = 0.063
  CI (99.9%): [2.258, 4.551] (assumes normal distribution)


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
# Warmup Iteration   1: 4.751 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.236 ±(99.9%) 0.003 ms/op
Iteration   1: 3.308 ±(99.9%) 0.002 ms/op
Iteration   2: 3.342 ±(99.9%) 0.002 ms/op
Iteration   3: 3.293 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.314 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (3.293, 3.314, 3.342), stdev = 0.025
  CI (99.9%): [2.852, 3.777] (assumes normal distribution)


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
# Warmup Iteration   1: 5.018 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.532 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.003 ms/op
Iteration   1: 3.478 ±(99.9%) 0.004 ms/op
Iteration   2: 3.294 ±(99.9%) 0.005 ms/op
Iteration   3: 3.421 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.398 ±(99.9%) 1.713 ms/op [Average]
  (min, avg, max) = (3.294, 3.398, 3.478), stdev = 0.094
  CI (99.9%): [1.685, 5.110] (assumes normal distribution)


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
# Warmup Iteration   1: 5.256 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.778 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.608 ±(99.9%) 0.014 ms/op
Iteration   1: 4.521 ±(99.9%) 0.043 ms/op
Iteration   2: 4.537 ±(99.9%) 0.015 ms/op
Iteration   3: 4.503 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.520 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (4.503, 4.520, 4.537), stdev = 0.017
  CI (99.9%): [4.209, 4.832] (assumes normal distribution)


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
# Warmup Iteration   1: 4.830 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.009 ms/op
Iteration   1: 3.473 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  11.463 ms/op
                 createUser·p0.9999: 16.662 ms/op
                 createUser·p1.00:   17.203 ms/op

Iteration   2: 3.380 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.162 ms/op
                 createUser·p0.99:   4.765 ms/op
                 createUser·p0.999:  7.234 ms/op
                 createUser·p0.9999: 17.269 ms/op
                 createUser·p1.00:   17.596 ms/op

Iteration   3: 3.284 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.628 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  9.387 ms/op
                 createUser·p0.9999: 20.891 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 284107
  mean =      3.377 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7591 
    [ 2.500,  5.000) = 274065 
    [ 5.000,  7.500) = 2073 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.153 ms/op
     p(99.0000) =      4.882 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     20.303 ms/op
     p(99.9990) =     21.760 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 4.458 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.315 ±(99.9%) 0.006 ms/op
Iteration   1: 3.206 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   4.014 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  6.876 ms/op
                 existUser·p0.9999: 15.500 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 3.331 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   4.702 ms/op
                 existUser·p0.999:  10.486 ms/op
                 existUser·p0.9999: 15.100 ms/op
                 existUser·p1.00:   17.400 ms/op

Iteration   3: 3.212 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   3.195 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.653 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 18.188 ms/op
                 existUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 295373
  mean =      3.249 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 481 
    [ 1.250,  2.500) = 12281 
    [ 2.500,  3.750) = 250153 
    [ 3.750,  5.000) = 30699 
    [ 5.000,  6.250) = 1144 
    [ 6.250,  7.500) = 253 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.002 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     17.445 ms/op
     p(99.9990) =     18.353 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 4.973 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.009 ms/op
Iteration   1: 3.381 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.840 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.259 ms/op
                 getUser·p0.999:  7.758 ms/op
                 getUser·p0.9999: 17.057 ms/op
                 getUser·p1.00:   18.547 ms/op

Iteration   2: 3.354 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.989 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  8.139 ms/op
                 getUser·p0.9999: 19.069 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   3: 3.359 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   4.080 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   5.251 ms/op
                 getUser·p0.999:  7.564 ms/op
                 getUser·p0.9999: 18.234 ms/op
                 getUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 285267
  mean =      3.364 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 396 
    [ 1.250,  2.500) = 13551 
    [ 2.500,  3.750) = 216722 
    [ 3.750,  5.000) = 50473 
    [ 5.000,  6.250) = 3314 
    [ 6.250,  7.500) = 485 
    [ 7.500,  8.750) = 153 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 87 
    [17.500, 18.750) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     18.267 ms/op
     p(99.9990) =     19.441 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 6.550 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.832 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.610 ±(99.9%) 0.012 ms/op
Iteration   1: 4.587 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.349 ms/op
                 listUser·p0.99:   7.864 ms/op
                 listUser·p0.999:  13.938 ms/op
                 listUser·p0.9999: 15.845 ms/op
                 listUser·p1.00:   16.220 ms/op

Iteration   2: 4.536 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.349 ms/op
                 listUser·p0.99:   7.774 ms/op
                 listUser·p0.999:  14.671 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   20.742 ms/op

Iteration   3: 4.394 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   4.243 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.997 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  17.538 ms/op
                 listUser·p0.9999: 21.585 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 213126
  mean =      4.504 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 538 
    [ 2.500,  5.000) = 180764 
    [ 5.000,  7.500) = 28836 
    [ 7.500, 10.000) = 2569 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     21.191 ms/op
     p(99.9990) =     21.627 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.469 ± 3.058  ops/ms
ClientGrpc.existUser                       thrpt       3  10.031 ± 2.025  ops/ms
ClientGrpc.getUser                         thrpt       3   9.524 ± 0.554  ops/ms
ClientGrpc.listUser                        thrpt       3   7.166 ± 1.290  ops/ms
ClientGrpc.createUser                       avgt       3   3.404 ± 1.147   ms/op
ClientGrpc.existUser                        avgt       3   3.314 ± 0.462   ms/op
ClientGrpc.getUser                          avgt       3   3.398 ± 1.713   ms/op
ClientGrpc.listUser                         avgt       3   4.520 ± 0.311   ms/op
ClientGrpc.createUser                     sample  284107   3.377 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.628           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.351           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.153           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.060           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.303           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  295373   3.249 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.673           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.232           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.002           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.716           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.445           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.514           ms/op
ClientGrpc.getUser                        sample  285267   3.364 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.684           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.330           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.010           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.267           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.758           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.267           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.628           ms/op
ClientGrpc.listUser                       sample  213126   4.504 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.967           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.375           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.341           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.210           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.713           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.191           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.118           ms/op
