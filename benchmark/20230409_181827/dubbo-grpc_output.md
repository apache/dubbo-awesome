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
# Warmup Iteration   1: 2.401 ops/ms
# Warmup Iteration   2: 5.509 ops/ms
# Warmup Iteration   3: 6.532 ops/ms
Iteration   1: 6.857 ops/ms
Iteration   2: 7.023 ops/ms
Iteration   3: 6.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.906 ±(99.9%) 1.859 ops/ms [Average]
  (min, avg, max) = (6.839, 6.906, 7.023), stdev = 0.102
  CI (99.9%): [5.048, 8.765] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.856 ops/ms
# Warmup Iteration   2: 7.360 ops/ms
# Warmup Iteration   3: 7.653 ops/ms
Iteration   1: 7.756 ops/ms
Iteration   2: 7.855 ops/ms
Iteration   3: 7.935 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.849 ±(99.9%) 1.634 ops/ms [Average]
  (min, avg, max) = (7.756, 7.849, 7.935), stdev = 0.090
  CI (99.9%): [6.215, 9.483] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.194 ops/ms
# Warmup Iteration   2: 6.849 ops/ms
# Warmup Iteration   3: 7.365 ops/ms
Iteration   1: 7.370 ops/ms
Iteration   2: 7.416 ops/ms
Iteration   3: 7.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.414 ±(99.9%) 0.802 ops/ms [Average]
  (min, avg, max) = (7.370, 7.414, 7.458), stdev = 0.044
  CI (99.9%): [6.612, 8.217] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.724 ops/ms
# Warmup Iteration   2: 5.318 ops/ms
# Warmup Iteration   3: 5.671 ops/ms
Iteration   1: 5.393 ops/ms
Iteration   2: 5.408 ops/ms
Iteration   3: 5.126 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.309 ±(99.9%) 2.895 ops/ms [Average]
  (min, avg, max) = (5.126, 5.309, 5.408), stdev = 0.159
  CI (99.9%): [2.414, 8.204] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.803 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.681 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.545 ±(99.9%) 0.013 ms/op
Iteration   1: 4.310 ±(99.9%) 0.005 ms/op
Iteration   2: 4.327 ±(99.9%) 0.002 ms/op
Iteration   3: 4.272 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.303 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (4.272, 4.303, 4.327), stdev = 0.028
  CI (99.9%): [3.790, 4.815] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.972 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.424 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.094 ±(99.9%) 0.003 ms/op
Iteration   1: 4.126 ±(99.9%) 0.003 ms/op
Iteration   2: 3.977 ±(99.9%) 0.003 ms/op
Iteration   3: 3.978 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.027 ±(99.9%) 1.559 ms/op [Average]
  (min, avg, max) = (3.977, 4.027, 4.126), stdev = 0.085
  CI (99.9%): [2.468, 5.586] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.660 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.876 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.613 ±(99.9%) 0.005 ms/op
Iteration   1: 4.345 ±(99.9%) 0.003 ms/op
Iteration   2: 4.485 ±(99.9%) 0.004 ms/op
Iteration   3: 4.509 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.446 ±(99.9%) 1.623 ms/op [Average]
  (min, avg, max) = (4.345, 4.446, 4.509), stdev = 0.089
  CI (99.9%): [2.824, 6.069] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.989 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 6.180 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.957 ±(99.9%) 0.023 ms/op
Iteration   1: 5.975 ±(99.9%) 0.023 ms/op
Iteration   2: 5.906 ±(99.9%) 0.024 ms/op
Iteration   3: 5.647 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.843 ±(99.9%) 3.160 ms/op [Average]
  (min, avg, max) = (5.647, 5.843, 5.975), stdev = 0.173
  CI (99.9%): [2.683, 9.002] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.614 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.791 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.520 ±(99.9%) 0.013 ms/op
Iteration   1: 4.551 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   4.424 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   8.298 ms/op
                 createUser·p0.999:  15.215 ms/op
                 createUser·p0.9999: 20.673 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 4.523 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   4.391 ms/op
                 createUser·p0.90:   5.661 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   7.896 ms/op
                 createUser·p0.999:  13.949 ms/op
                 createUser·p0.9999: 19.227 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   3: 4.391 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   5.882 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  10.670 ms/op
                 createUser·p0.9999: 21.028 ms/op
                 createUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214050
  mean =      4.487 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3619 
    [ 2.500,  5.000) = 161067 
    [ 5.000,  7.500) = 46745 
    [ 7.500, 10.000) = 1959 
    [10.000, 12.500) = 360 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      4.366 ms/op
     p(90.0000) =      5.612 ms/op
     p(95.0000) =      6.070 ms/op
     p(99.0000) =      7.889 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     21.290 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.472 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.428 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.257 ±(99.9%) 0.013 ms/op
Iteration   1: 4.258 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   4.178 ms/op
                 existUser·p0.90:   5.210 ms/op
                 existUser·p0.95:   5.554 ms/op
                 existUser·p0.99:   6.545 ms/op
                 existUser·p0.999:  12.072 ms/op
                 existUser·p0.9999: 19.266 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   2: 4.191 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   4.059 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   5.521 ms/op
                 existUser·p0.99:   7.111 ms/op
                 existUser·p0.999:  11.339 ms/op
                 existUser·p0.9999: 16.118 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   3: 4.205 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.021 ms/op
                 existUser·p0.50:   4.100 ms/op
                 existUser·p0.90:   5.136 ms/op
                 existUser·p0.95:   5.480 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  11.891 ms/op
                 existUser·p0.9999: 22.505 ms/op
                 existUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 227530
  mean =      4.218 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3096 
    [ 2.500,  5.000) = 193436 
    [ 5.000,  7.500) = 29439 
    [ 7.500, 10.000) = 1134 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.021 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     11.649 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     22.920 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.355 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.008 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.664 ±(99.9%) 0.012 ms/op
Iteration   1: 4.420 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.030 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.571 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   7.545 ms/op
                 getUser·p0.999:  11.037 ms/op
                 getUser·p0.9999: 25.765 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   2: 4.608 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   4.465 ms/op
                 getUser·p0.90:   5.661 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   8.315 ms/op
                 getUser·p0.999:  13.739 ms/op
                 getUser·p0.9999: 24.815 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   3: 4.676 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   4.547 ms/op
                 getUser·p0.90:   5.890 ms/op
                 getUser·p0.95:   6.431 ms/op
                 getUser·p0.99:   8.634 ms/op
                 getUser·p0.999:  13.402 ms/op
                 getUser·p0.9999: 22.522 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 210190
  mean =      4.566 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3596 
    [ 2.500,  5.000) = 152038 
    [ 5.000,  7.500) = 51489 
    [ 7.500, 10.000) = 2375 
    [10.000, 12.500) = 410 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     13.170 ms/op
     p(99.9900) =     25.099 ms/op
     p(99.9990) =     26.477 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.050 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 6.486 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.829 ±(99.9%) 0.020 ms/op
Iteration   1: 5.783 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.565 ms/op
                 listUser·p0.50:   5.521 ms/op
                 listUser·p0.90:   7.479 ms/op
                 listUser·p0.95:   8.405 ms/op
                 listUser·p0.99:   10.830 ms/op
                 listUser·p0.999:  18.472 ms/op
                 listUser·p0.9999: 23.150 ms/op
                 listUser·p1.00:   23.757 ms/op

Iteration   2: 5.706 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.718 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.266 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  20.870 ms/op
                 listUser·p0.9999: 28.914 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   3: 5.608 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.241 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   7.987 ms/op
                 listUser·p0.99:   9.945 ms/op
                 listUser·p0.999:  19.093 ms/op
                 listUser·p0.9999: 30.606 ms/op
                 listUser·p1.00:   31.130 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168478
  mean =      5.698 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 111 
    [ 2.500,  5.000) = 49979 
    [ 5.000,  7.500) = 104072 
    [ 7.500, 10.000) = 11887 
    [10.000, 12.500) = 1797 
    [12.500, 15.000) = 306 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.565 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     10.551 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     28.949 ms/op
     p(99.9990) =     31.107 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.906 ± 1.859  ops/ms
ClientGrpc.existUser                       thrpt       3   7.849 ± 1.634  ops/ms
ClientGrpc.getUser                         thrpt       3   7.414 ± 0.802  ops/ms
ClientGrpc.listUser                        thrpt       3   5.309 ± 2.895  ops/ms
ClientGrpc.createUser                       avgt       3   4.303 ± 0.513   ms/op
ClientGrpc.existUser                        avgt       3   4.027 ± 1.559   ms/op
ClientGrpc.getUser                          avgt       3   4.446 ± 1.623   ms/op
ClientGrpc.listUser                         avgt       3   5.843 ± 3.160   ms/op
ClientGrpc.createUser                     sample  214050   4.487 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.717           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.612           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.070           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.889           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.270           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.677           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.299           ms/op
ClientGrpc.existUser                      sample  227530   4.218 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.021           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.169           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.521           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.816           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.649           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.709           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.036           ms/op
ClientGrpc.getUser                        sample  210190   4.566 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.943           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.710           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.210           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.143           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.170           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.099           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.034           ms/op
ClientGrpc.listUser                       sample  168478   5.698 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.565           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.249           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.551           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.333           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.949           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.130           ms/op
