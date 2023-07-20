# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.986 ops/ms
# Warmup Iteration   2: 4.889 ops/ms
# Warmup Iteration   3: 5.691 ops/ms
Iteration   1: 6.302 ops/ms
Iteration   2: 6.786 ops/ms
Iteration   3: 6.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.564 ±(99.9%) 4.468 ops/ms [Average]
  (min, avg, max) = (6.302, 6.564, 6.786), stdev = 0.245
  CI (99.9%): [2.096, 11.033] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.821 ops/ms
# Warmup Iteration   2: 6.252 ops/ms
# Warmup Iteration   3: 7.047 ops/ms
Iteration   1: 6.829 ops/ms
Iteration   2: 5.943 ops/ms
Iteration   3: 6.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.499 ±(99.9%) 8.836 ops/ms [Average]
  (min, avg, max) = (5.943, 6.499, 6.829), stdev = 0.484
  CI (99.9%): [≈ 0, 15.335] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.308 ops/ms
# Warmup Iteration   2: 6.129 ops/ms
# Warmup Iteration   3: 6.382 ops/ms
Iteration   1: 5.945 ops/ms
Iteration   2: 6.594 ops/ms
Iteration   3: 6.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.358 ±(99.9%) 6.549 ops/ms [Average]
  (min, avg, max) = (5.945, 6.358, 6.594), stdev = 0.359
  CI (99.9%): [≈ 0, 12.907] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.749 ops/ms
# Warmup Iteration   2: 3.805 ops/ms
# Warmup Iteration   3: 4.407 ops/ms
Iteration   1: 4.538 ops/ms
Iteration   2: 4.417 ops/ms
Iteration   3: 4.429 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.461 ±(99.9%) 1.223 ops/ms [Average]
  (min, avg, max) = (4.417, 4.461, 4.538), stdev = 0.067
  CI (99.9%): [3.238, 5.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.319 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.678 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.951 ±(99.9%) 0.027 ms/op
Iteration   1: 6.437 ±(99.9%) 0.007 ms/op
Iteration   2: 4.949 ±(99.9%) 0.006 ms/op
Iteration   3: 4.833 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  5.406 ±(99.9%) 16.315 ms/op [Average]
  (min, avg, max) = (4.833, 5.406, 6.437), stdev = 0.894
  CI (99.9%): [≈ 0, 21.721] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.588 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.883 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.745 ±(99.9%) 0.021 ms/op
Iteration   1: 4.850 ±(99.9%) 0.006 ms/op
Iteration   2: 4.443 ±(99.9%) 0.005 ms/op
Iteration   3: 4.348 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.547 ±(99.9%) 4.872 ms/op [Average]
  (min, avg, max) = (4.348, 4.547, 4.850), stdev = 0.267
  CI (99.9%): [≈ 0, 9.419] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.258 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.316 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.818 ±(99.9%) 0.004 ms/op
Iteration   1: 4.849 ±(99.9%) 0.003 ms/op
Iteration   2: 4.959 ±(99.9%) 0.004 ms/op
Iteration   3: 4.918 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.908 ±(99.9%) 1.016 ms/op [Average]
  (min, avg, max) = (4.849, 4.908, 4.959), stdev = 0.056
  CI (99.9%): [3.893, 5.924] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.699 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 6.677 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.116 ±(99.9%) 0.020 ms/op
Iteration   1: 6.215 ±(99.9%) 0.020 ms/op
Iteration   2: 5.935 ±(99.9%) 0.022 ms/op
Iteration   3: 6.071 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.074 ±(99.9%) 2.557 ms/op [Average]
  (min, avg, max) = (5.935, 6.074, 6.215), stdev = 0.140
  CI (99.9%): [3.517, 8.631] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.792 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.206 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.761 ±(99.9%) 0.016 ms/op
Iteration   1: 4.754 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.229 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   6.185 ms/op
                 createUser·p0.95:   6.980 ms/op
                 createUser·p0.99:   9.076 ms/op
                 createUser·p0.999:  13.550 ms/op
                 createUser·p0.9999: 18.278 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   2: 4.715 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.094 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   5.906 ms/op
                 createUser·p0.95:   6.570 ms/op
                 createUser·p0.99:   8.782 ms/op
                 createUser·p0.999:  15.221 ms/op
                 createUser·p0.9999: 22.333 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 4.420 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.480 ms/op
                 createUser·p0.95:   5.956 ms/op
                 createUser·p0.99:   7.624 ms/op
                 createUser·p0.999:  13.822 ms/op
                 createUser·p0.9999: 22.086 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 207442
  mean =      4.625 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1547 
    [ 2.500,  5.000) = 150945 
    [ 5.000,  7.500) = 50325 
    [ 7.500, 10.000) = 3710 
    [10.000, 12.500) = 518 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.849 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     22.638 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.632 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.140 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.095 ±(99.9%) 0.021 ms/op
Iteration   1: 5.040 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   6.545 ms/op
                 existUser·p0.95:   7.520 ms/op
                 existUser·p0.99:   9.988 ms/op
                 existUser·p0.999:  13.320 ms/op
                 existUser·p0.9999: 22.696 ms/op
                 existUser·p1.00:   23.396 ms/op

Iteration   2: 4.632 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.971 ms/op
                 existUser·p0.50:   4.432 ms/op
                 existUser·p0.90:   5.964 ms/op
                 existUser·p0.95:   6.668 ms/op
                 existUser·p0.99:   9.039 ms/op
                 existUser·p0.999:  13.525 ms/op
                 existUser·p0.9999: 23.737 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   3: 4.543 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.102 ms/op
                 existUser·p0.50:   4.309 ms/op
                 existUser·p0.90:   5.906 ms/op
                 existUser·p0.95:   6.627 ms/op
                 existUser·p0.99:   9.241 ms/op
                 existUser·p0.999:  16.189 ms/op
                 existUser·p0.9999: 23.819 ms/op
                 existUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 203005
  mean =      4.729 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4610 
    [ 2.500,  5.000) = 132498 
    [ 5.000,  7.500) = 58940 
    [ 7.500, 10.000) = 5435 
    [10.000, 12.500) = 1018 
    [12.500, 15.000) = 348 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      6.947 ms/op
     p(99.0000) =      9.470 ms/op
     p(99.9000) =     13.943 ms/op
     p(99.9900) =     23.573 ms/op
     p(99.9990) =     26.280 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.719 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 5.548 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.070 ±(99.9%) 0.019 ms/op
Iteration   1: 5.170 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.930 ms/op
                 getUser·p0.95:   7.856 ms/op
                 getUser·p0.99:   10.459 ms/op
                 getUser·p0.999:  14.619 ms/op
                 getUser·p0.9999: 22.979 ms/op
                 getUser·p1.00:   23.626 ms/op

Iteration   2: 5.106 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   4.776 ms/op
                 getUser·p0.90:   6.988 ms/op
                 getUser·p0.95:   8.241 ms/op
                 getUser·p0.99:   11.294 ms/op
                 getUser·p0.999:  15.674 ms/op
                 getUser·p0.9999: 23.551 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 5.182 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.208 ms/op
                 getUser·p0.50:   4.841 ms/op
                 getUser·p0.90:   6.930 ms/op
                 getUser·p0.95:   8.282 ms/op
                 getUser·p0.99:   11.617 ms/op
                 getUser·p0.999:  15.553 ms/op
                 getUser·p0.9999: 26.269 ms/op
                 getUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 186224
  mean =      5.152 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3184 
    [ 2.500,  5.000) = 101727 
    [ 5.000,  7.500) = 68183 
    [ 7.500, 10.000) = 9757 
    [10.000, 12.500) = 2395 
    [12.500, 15.000) = 742 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.015 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.955 ms/op
     p(95.0000) =      8.094 ms/op
     p(99.0000) =     11.125 ms/op
     p(99.9000) =     15.463 ms/op
     p(99.9900) =     24.056 ms/op
     p(99.9990) =     26.434 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.360 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 7.192 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.654 ±(99.9%) 0.036 ms/op
Iteration   1: 6.560 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   2.025 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   9.388 ms/op
                 listUser·p0.95:   10.617 ms/op
                 listUser·p0.99:   13.713 ms/op
                 listUser·p0.999:  21.274 ms/op
                 listUser·p0.9999: 24.064 ms/op
                 listUser·p1.00:   24.314 ms/op

Iteration   2: 6.408 ±(99.9%) 0.032 ms/op
                 listUser·p0.00:   1.845 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   9.060 ms/op
                 listUser·p0.95:   10.273 ms/op
                 listUser·p0.99:   13.484 ms/op
                 listUser·p0.999:  22.971 ms/op
                 listUser·p0.9999: 29.721 ms/op
                 listUser·p1.00:   31.523 ms/op

Iteration   3: 6.665 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.560 ms/op
                 listUser·p0.50:   5.964 ms/op
                 listUser·p0.90:   9.552 ms/op
                 listUser·p0.95:   11.239 ms/op
                 listUser·p0.99:   15.991 ms/op
                 listUser·p0.999:  31.094 ms/op
                 listUser·p0.9999: 39.387 ms/op
                 listUser·p1.00:   39.780 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 146786
  mean =      6.542 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 32455 
    [ 5.000,  7.500) = 78585 
    [ 7.500, 10.000) = 25350 
    [10.000, 12.500) = 7028 
    [12.500, 15.000) = 2112 
    [15.000, 17.500) = 546 
    [17.500, 20.000) = 246 
    [20.000, 22.500) = 158 
    [22.500, 25.000) = 88 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      5.939 ms/op
     p(90.0000) =      9.322 ms/op
     p(95.0000) =     10.666 ms/op
     p(99.0000) =     14.369 ms/op
     p(99.9000) =     24.819 ms/op
     p(99.9900) =     35.883 ms/op
     p(99.9990) =     39.688 ms/op
     p(99.9999) =     39.780 ms/op
    p(100.0000) =     39.780 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score    Error   Units
ClientGrpc.createUser                      thrpt       3   6.564 ±  4.468  ops/ms
ClientGrpc.existUser                       thrpt       3   6.499 ±  8.836  ops/ms
ClientGrpc.getUser                         thrpt       3   6.358 ±  6.549  ops/ms
ClientGrpc.listUser                        thrpt       3   4.461 ±  1.223  ops/ms
ClientGrpc.createUser                       avgt       3   5.406 ± 16.315   ms/op
ClientGrpc.existUser                        avgt       3   4.547 ±  4.872   ms/op
ClientGrpc.getUser                          avgt       3   4.908 ±  1.016   ms/op
ClientGrpc.listUser                         avgt       3   6.074 ±  2.557   ms/op
ClientGrpc.createUser                     sample  207442   4.625 ±  0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.094            ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.415            ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.849            ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.513            ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.667            ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.385            ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.086            ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.150            ms/op
ClientGrpc.existUser                      sample  203005   4.729 ±  0.010   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.783            ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.506            ms/op
ClientGrpc.existUser:existUser·p0.90      sample           6.144            ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.947            ms/op
ClientGrpc.existUser:existUser·p0.99      sample           9.470            ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.943            ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.573            ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.280            ms/op
ClientGrpc.getUser                        sample  186224   5.152 ±  0.012   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.015            ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.825            ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.955            ms/op
ClientGrpc.getUser:getUser·p0.95          sample           8.094            ms/op
ClientGrpc.getUser:getUser·p0.99          sample          11.125            ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.463            ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.056            ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.575            ms/op
ClientGrpc.listUser                       sample  146786   6.542 ±  0.020   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.560            ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.939            ms/op
ClientGrpc.listUser:listUser·p0.90        sample           9.322            ms/op
ClientGrpc.listUser:listUser·p0.95        sample          10.666            ms/op
ClientGrpc.listUser:listUser·p0.99        sample          14.369            ms/op
ClientGrpc.listUser:listUser·p0.999       sample          24.819            ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.883            ms/op
ClientGrpc.listUser:listUser·p1.00        sample          39.780            ms/op
