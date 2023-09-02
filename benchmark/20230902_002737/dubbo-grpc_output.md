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
# Warmup Iteration   1: 1.199 ops/ms
# Warmup Iteration   2: 2.661 ops/ms
# Warmup Iteration   3: 4.760 ops/ms
Iteration   1: 5.631 ops/ms
Iteration   2: 6.356 ops/ms
Iteration   3: 6.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.120 ±(99.9%) 7.723 ops/ms [Average]
  (min, avg, max) = (5.631, 6.120, 6.372), stdev = 0.423
  CI (99.9%): [≈ 0, 13.843] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.951 ops/ms
# Warmup Iteration   2: 5.397 ops/ms
# Warmup Iteration   3: 5.692 ops/ms
Iteration   1: 5.994 ops/ms
Iteration   2: 6.096 ops/ms
Iteration   3: 5.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.029 ±(99.9%) 1.064 ops/ms [Average]
  (min, avg, max) = (5.994, 6.029, 6.096), stdev = 0.058
  CI (99.9%): [4.965, 7.093] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.442 ops/ms
# Warmup Iteration   2: 4.616 ops/ms
# Warmup Iteration   3: 5.415 ops/ms
Iteration   1: 5.524 ops/ms
Iteration   2: 5.236 ops/ms
Iteration   3: 5.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.396 ±(99.9%) 2.684 ops/ms [Average]
  (min, avg, max) = (5.236, 5.396, 5.524), stdev = 0.147
  CI (99.9%): [2.713, 8.080] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.625 ops/ms
# Warmup Iteration   2: 3.796 ops/ms
# Warmup Iteration   3: 4.706 ops/ms
Iteration   1: 4.253 ops/ms
Iteration   2: 3.548 ops/ms
Iteration   3: 3.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.807 ±(99.9%) 7.077 ops/ms [Average]
  (min, avg, max) = (3.548, 3.807, 4.253), stdev = 0.388
  CI (99.9%): [≈ 0, 10.884] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:55
# Fork: 1 of 1
# Warmup Iteration   1: 13.619 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 7.359 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.486 ±(99.9%) 0.018 ms/op
Iteration   1: 5.737 ±(99.9%) 0.007 ms/op
Iteration   2: 5.215 ±(99.9%) 0.003 ms/op
Iteration   3: 5.848 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.600 ±(99.9%) 6.160 ms/op [Average]
  (min, avg, max) = (5.215, 5.600, 5.848), stdev = 0.338
  CI (99.9%): [≈ 0, 11.760] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.734 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.721 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.344 ±(99.9%) 0.004 ms/op
Iteration   1: 5.182 ±(99.9%) 0.004 ms/op
Iteration   2: 5.287 ±(99.9%) 0.005 ms/op
Iteration   3: 6.034 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  5.501 ±(99.9%) 8.470 ms/op [Average]
  (min, avg, max) = (5.182, 5.501, 6.034), stdev = 0.464
  CI (99.9%): [≈ 0, 13.971] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.352 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 6.557 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.891 ±(99.9%) 0.008 ms/op
Iteration   1: 5.739 ±(99.9%) 0.004 ms/op
Iteration   2: 5.791 ±(99.9%) 0.005 ms/op
Iteration   3: 5.919 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  5.816 ±(99.9%) 1.683 ms/op [Average]
  (min, avg, max) = (5.739, 5.816, 5.919), stdev = 0.092
  CI (99.9%): [4.133, 7.500] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.693 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 8.449 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 7.049 ±(99.9%) 0.025 ms/op
Iteration   1: 6.832 ±(99.9%) 0.017 ms/op
Iteration   2: 6.977 ±(99.9%) 0.027 ms/op
Iteration   3: 6.819 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.876 ±(99.9%) 1.603 ms/op [Average]
  (min, avg, max) = (6.819, 6.876, 6.977), stdev = 0.088
  CI (99.9%): [5.273, 8.479] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.871 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 7.230 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.065 ±(99.9%) 0.027 ms/op
Iteration   1: 5.597 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.444 ms/op
                 createUser·p0.50:   5.317 ms/op
                 createUser·p0.90:   7.479 ms/op
                 createUser·p0.95:   8.380 ms/op
                 createUser·p0.99:   11.333 ms/op
                 createUser·p0.999:  14.909 ms/op
                 createUser·p0.9999: 28.742 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   2: 5.340 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.618 ms/op
                 createUser·p0.50:   5.153 ms/op
                 createUser·p0.90:   6.881 ms/op
                 createUser·p0.95:   7.578 ms/op
                 createUser·p0.99:   9.492 ms/op
                 createUser·p0.999:  27.239 ms/op
                 createUser·p0.9999: 35.128 ms/op
                 createUser·p1.00:   35.717 ms/op

Iteration   3: 5.831 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   1.565 ms/op
                 createUser·p0.50:   5.480 ms/op
                 createUser·p0.90:   8.086 ms/op
                 createUser·p0.95:   9.257 ms/op
                 createUser·p0.99:   12.173 ms/op
                 createUser·p0.999:  15.980 ms/op
                 createUser·p0.9999: 34.440 ms/op
                 createUser·p1.00:   37.749 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 171819
  mean =      5.582 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 878 
    [ 2.500,  5.000) = 68735 
    [ 5.000,  7.500) = 85483 
    [ 7.500, 10.000) = 13270 
    [10.000, 12.500) = 2484 
    [12.500, 15.000) = 713 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.444 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      7.463 ms/op
     p(95.0000) =      8.421 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     15.666 ms/op
     p(99.9900) =     34.132 ms/op
     p(99.9990) =     36.572 ms/op
     p(99.9999) =     37.749 ms/op
    p(100.0000) =     37.749 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 8.315 ±(99.9%) 0.119 ms/op
# Warmup Iteration   2: 6.317 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.650 ±(99.9%) 0.022 ms/op
Iteration   1: 5.646 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   5.341 ms/op
                 existUser·p0.90:   7.569 ms/op
                 existUser·p0.95:   8.765 ms/op
                 existUser·p0.99:   11.239 ms/op
                 existUser·p0.999:  15.783 ms/op
                 existUser·p0.9999: 21.267 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 5.528 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   7.406 ms/op
                 existUser·p0.95:   8.520 ms/op
                 existUser·p0.99:   11.990 ms/op
                 existUser·p0.999:  20.414 ms/op
                 existUser·p0.9999: 30.607 ms/op
                 existUser·p1.00:   31.261 ms/op

Iteration   3: 5.183 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   4.956 ms/op
                 existUser·p0.90:   6.873 ms/op
                 existUser·p0.95:   7.684 ms/op
                 existUser·p0.99:   9.978 ms/op
                 existUser·p0.999:  16.630 ms/op
                 existUser·p0.9999: 22.746 ms/op
                 existUser·p1.00:   23.724 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 176257
  mean =      5.445 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1455 
    [ 2.500,  5.000) = 78143 
    [ 5.000,  7.500) = 81695 
    [ 7.500, 10.000) = 11857 
    [10.000, 12.500) = 2074 
    [12.500, 15.000) = 687 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.298 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     17.990 ms/op
     p(99.9900) =     25.964 ms/op
     p(99.9990) =     31.161 ms/op
     p(99.9999) =     31.261 ms/op
    p(100.0000) =     31.261 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 9.110 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 5.847 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.637 ±(99.9%) 0.022 ms/op
Iteration   1: 5.493 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   5.235 ms/op
                 getUser·p0.90:   7.176 ms/op
                 getUser·p0.95:   8.012 ms/op
                 getUser·p0.99:   10.732 ms/op
                 getUser·p0.999:  16.217 ms/op
                 getUser·p0.9999: 20.235 ms/op
                 getUser·p1.00:   21.070 ms/op

Iteration   2: 5.204 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   4.997 ms/op
                 getUser·p0.90:   6.783 ms/op
                 getUser·p0.95:   7.537 ms/op
                 getUser·p0.99:   9.945 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 35.848 ms/op
                 getUser·p1.00:   36.372 ms/op

Iteration   3: 5.155 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.122 ms/op
                 getUser·p0.50:   4.981 ms/op
                 getUser·p0.90:   6.652 ms/op
                 getUser·p0.95:   7.463 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  13.206 ms/op
                 getUser·p0.9999: 28.187 ms/op
                 getUser·p1.00:   32.408 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 181741
  mean =      5.280 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2265 
    [ 2.500,  5.000) = 84531 
    [ 5.000,  7.500) = 84276 
    [ 7.500, 10.000) = 8743 
    [10.000, 12.500) = 1365 
    [12.500, 15.000) = 335 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 13 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      5.063 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      7.692 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     15.848 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     36.212 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.020 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 7.511 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 6.773 ±(99.9%) 0.033 ms/op
Iteration   1: 6.986 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   6.537 ms/op
                 listUser·p0.90:   9.667 ms/op
                 listUser·p0.95:   10.912 ms/op
                 listUser·p0.99:   13.910 ms/op
                 listUser·p0.999:  25.178 ms/op
                 listUser·p0.9999: 29.305 ms/op
                 listUser·p1.00:   30.212 ms/op

Iteration   2: 6.589 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   1.489 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   9.142 ms/op
                 listUser·p0.95:   10.322 ms/op
                 listUser·p0.99:   13.468 ms/op
                 listUser·p0.999:  20.004 ms/op
                 listUser·p0.9999: 23.663 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   3: 6.571 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   6.136 ms/op
                 listUser·p0.90:   8.831 ms/op
                 listUser·p0.95:   10.043 ms/op
                 listUser·p0.99:   13.320 ms/op
                 listUser·p0.999:  24.488 ms/op
                 listUser·p0.9999: 28.720 ms/op
                 listUser·p1.00:   29.262 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 143017
  mean =      6.710 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 21724 
    [ 5.000,  7.500) = 83988 
    [ 7.500, 10.000) = 28038 
    [10.000, 12.500) = 6837 
    [12.500, 15.000) = 1581 
    [15.000, 17.500) = 439 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.489 ms/op
     p(50.0000) =      6.250 ms/op
     p(90.0000) =      9.241 ms/op
     p(95.0000) =     10.453 ms/op
     p(99.0000) =     13.615 ms/op
     p(99.9000) =     21.725 ms/op
     p(99.9900) =     28.246 ms/op
     p(99.9990) =     30.128 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


# Run complete. Total time: 00:13:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.120 ± 7.723  ops/ms
ClientGrpc.existUser                       thrpt       3   6.029 ± 1.064  ops/ms
ClientGrpc.getUser                         thrpt       3   5.396 ± 2.684  ops/ms
ClientGrpc.listUser                        thrpt       3   3.807 ± 7.077  ops/ms
ClientGrpc.createUser                       avgt       3   5.600 ± 6.160   ms/op
ClientGrpc.existUser                        avgt       3   5.501 ± 8.470   ms/op
ClientGrpc.getUser                          avgt       3   5.816 ± 1.683   ms/op
ClientGrpc.listUser                         avgt       3   6.876 ± 1.603   ms/op
ClientGrpc.createUser                     sample  171819   5.582 ± 0.014   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.444           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           5.300           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           7.463           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           8.421           ms/op
ClientGrpc.createUser:createUser·p0.99    sample          11.354           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.666           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.132           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          37.749           ms/op
ClientGrpc.existUser                      sample  176257   5.445 ± 0.013   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.077           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           5.145           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           7.274           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           8.298           ms/op
ClientGrpc.existUser:existUser·p0.99      sample          11.141           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          17.990           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.964           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.261           ms/op
ClientGrpc.getUser                        sample  181741   5.280 ± 0.011   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.104           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           5.063           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.881           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           7.692           ms/op
ClientGrpc.getUser:getUser·p0.99          sample          10.125           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.848           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.062           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.372           ms/op
ClientGrpc.listUser                       sample  143017   6.710 ± 0.018   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.489           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           6.250           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           9.241           ms/op
ClientGrpc.listUser:listUser·p0.95        sample          10.453           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          13.615           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.725           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.246           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.212           ms/op
