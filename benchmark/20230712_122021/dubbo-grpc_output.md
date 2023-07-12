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
# Warmup Iteration   1: 2.255 ops/ms
# Warmup Iteration   2: 5.198 ops/ms
# Warmup Iteration   3: 6.736 ops/ms
Iteration   1: 7.167 ops/ms
Iteration   2: 7.211 ops/ms
Iteration   3: 7.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.260 ±(99.9%) 2.260 ops/ms [Average]
  (min, avg, max) = (7.167, 7.260, 7.401), stdev = 0.124
  CI (99.9%): [4.999, 9.520] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.513 ops/ms
# Warmup Iteration   2: 7.013 ops/ms
# Warmup Iteration   3: 7.597 ops/ms
Iteration   1: 7.699 ops/ms
Iteration   2: 7.591 ops/ms
Iteration   3: 7.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.690 ±(99.9%) 1.724 ops/ms [Average]
  (min, avg, max) = (7.591, 7.690, 7.780), stdev = 0.095
  CI (99.9%): [5.966, 9.414] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.278 ops/ms
# Warmup Iteration   2: 6.942 ops/ms
# Warmup Iteration   3: 7.246 ops/ms
Iteration   1: 7.564 ops/ms
Iteration   2: 7.489 ops/ms
Iteration   3: 7.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.539 ±(99.9%) 0.786 ops/ms [Average]
  (min, avg, max) = (7.489, 7.539, 7.564), stdev = 0.043
  CI (99.9%): [6.753, 8.325] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.054 ops/ms
# Warmup Iteration   2: 4.797 ops/ms
# Warmup Iteration   3: 5.499 ops/ms
Iteration   1: 5.477 ops/ms
Iteration   2: 5.501 ops/ms
Iteration   3: 5.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.551 ±(99.9%) 1.959 ops/ms [Average]
  (min, avg, max) = (5.477, 5.551, 5.674), stdev = 0.107
  CI (99.9%): [3.591, 7.510] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.445 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.666 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.607 ±(99.9%) 0.013 ms/op
Iteration   1: 4.539 ±(99.9%) 0.003 ms/op
Iteration   2: 4.352 ±(99.9%) 0.003 ms/op
Iteration   3: 4.389 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.427 ±(99.9%) 1.808 ms/op [Average]
  (min, avg, max) = (4.352, 4.427, 4.539), stdev = 0.099
  CI (99.9%): [2.619, 6.235] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 5.847 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.351 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.221 ±(99.9%) 0.004 ms/op
Iteration   1: 4.168 ±(99.9%) 0.003 ms/op
Iteration   2: 4.076 ±(99.9%) 0.004 ms/op
Iteration   3: 4.034 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.093 ±(99.9%) 1.251 ms/op [Average]
  (min, avg, max) = (4.034, 4.093, 4.168), stdev = 0.069
  CI (99.9%): [2.842, 5.343] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.507 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.485 ±(99.9%) 0.003 ms/op
Iteration   1: 4.311 ±(99.9%) 0.006 ms/op
Iteration   2: 4.323 ±(99.9%) 0.003 ms/op
Iteration   3: 4.273 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.302 ±(99.9%) 0.479 ms/op [Average]
  (min, avg, max) = (4.273, 4.302, 4.323), stdev = 0.026
  CI (99.9%): [3.824, 4.781] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.066 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.944 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.642 ±(99.9%) 0.016 ms/op
Iteration   1: 5.632 ±(99.9%) 0.016 ms/op
Iteration   2: 5.828 ±(99.9%) 0.034 ms/op
Iteration   3: 5.671 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.710 ±(99.9%) 1.892 ms/op [Average]
  (min, avg, max) = (5.632, 5.710, 5.828), stdev = 0.104
  CI (99.9%): [3.819, 7.602] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.169 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.013 ms/op
Iteration   1: 4.095 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   6.646 ms/op
                 createUser·p0.999:  11.158 ms/op
                 createUser·p0.9999: 33.299 ms/op
                 createUser·p1.00:   33.751 ms/op

Iteration   2: 4.145 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   4.026 ms/op
                 createUser·p0.90:   5.169 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  15.529 ms/op
                 createUser·p0.9999: 23.406 ms/op
                 createUser·p1.00:   23.986 ms/op

Iteration   3: 4.087 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   6.963 ms/op
                 createUser·p0.999:  13.359 ms/op
                 createUser·p0.9999: 23.631 ms/op
                 createUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 233542
  mean =      4.109 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5522 
    [ 2.500,  5.000) = 197958 
    [ 5.000,  7.500) = 28518 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.769 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     13.155 ms/op
     p(99.9900) =     32.199 ms/op
     p(99.9990) =     33.642 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.765 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.010 ms/op
Iteration   1: 3.917 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.975 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.349 ms/op
                 existUser·p0.99:   6.851 ms/op
                 existUser·p0.999:  12.285 ms/op
                 existUser·p0.9999: 16.727 ms/op
                 existUser·p1.00:   19.202 ms/op

Iteration   2: 4.023 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  11.427 ms/op
                 existUser·p0.9999: 19.303 ms/op
                 existUser·p1.00:   19.792 ms/op

Iteration   3: 3.836 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.877 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.817 ms/op
                 existUser·p0.95:   5.218 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 30.212 ms/op
                 existUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 244663
  mean =      3.924 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7831 
    [ 2.500,  5.000) = 215569 
    [ 5.000,  7.500) = 19630 
    [ 7.500, 10.000) = 1178 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 9 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.341 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     11.463 ms/op
     p(99.9900) =     29.967 ms/op
     p(99.9990) =     30.296 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.320 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.013 ms/op
Iteration   1: 4.141 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.022 ms/op
                 getUser·p0.50:   4.047 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  9.699 ms/op
                 getUser·p0.9999: 18.809 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   2: 4.222 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   4.116 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.759 ms/op
                 getUser·p0.99:   7.725 ms/op
                 getUser·p0.999:  11.851 ms/op
                 getUser·p0.9999: 28.371 ms/op
                 getUser·p1.00:   31.687 ms/op

Iteration   3: 4.269 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   4.137 ms/op
                 getUser·p0.90:   5.235 ms/op
                 getUser·p0.95:   5.685 ms/op
                 getUser·p0.99:   7.823 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 25.985 ms/op
                 getUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 228152
  mean =      4.210 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4010 
    [ 2.500,  5.000) = 190835 
    [ 5.000,  7.500) = 31146 
    [ 7.500, 10.000) = 1635 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      4.100 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.389 ms/op
     p(99.9000) =     11.665 ms/op
     p(99.9900) =     25.550 ms/op
     p(99.9990) =     31.528 ms/op
     p(99.9999) =     31.687 ms/op
    p(100.0000) =     31.687 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.956 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.633 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.589 ±(99.9%) 0.022 ms/op
Iteration   1: 5.555 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   0.882 ms/op
                 listUser·p0.50:   5.284 ms/op
                 listUser·p0.90:   7.356 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  17.316 ms/op
                 listUser·p0.9999: 24.920 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   2: 5.458 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   8.454 ms/op
                 listUser·p0.99:   11.043 ms/op
                 listUser·p0.999:  17.806 ms/op
                 listUser·p0.9999: 25.086 ms/op
                 listUser·p1.00:   25.887 ms/op

Iteration   3: 5.532 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   7.504 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   11.076 ms/op
                 listUser·p0.999:  22.136 ms/op
                 listUser·p0.9999: 35.090 ms/op
                 listUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173976
  mean =      5.515 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 363 
    [ 2.500,  5.000) = 72448 
    [ 5.000,  7.500) = 84494 
    [ 7.500, 10.000) = 13857 
    [10.000, 12.500) = 1986 
    [12.500, 15.000) = 417 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     10.846 ms/op
     p(99.9000) =     18.350 ms/op
     p(99.9900) =     33.751 ms/op
     p(99.9990) =     35.882 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.260 ± 2.260  ops/ms
ClientGrpc.existUser                       thrpt       3   7.690 ± 1.724  ops/ms
ClientGrpc.getUser                         thrpt       3   7.539 ± 0.786  ops/ms
ClientGrpc.listUser                        thrpt       3   5.551 ± 1.959  ops/ms
ClientGrpc.createUser                       avgt       3   4.427 ± 1.808   ms/op
ClientGrpc.existUser                        avgt       3   4.093 ± 1.251   ms/op
ClientGrpc.getUser                          avgt       3   4.302 ± 0.479   ms/op
ClientGrpc.listUser                         avgt       3   5.710 ± 1.892   ms/op
ClientGrpc.createUser                     sample  233542   4.109 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.769           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.603           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.947           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.155           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.199           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.751           ms/op
ClientGrpc.existUser                      sample  244663   3.924 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.863           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.915           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.341           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.881           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.463           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.967           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.293           ms/op
ClientGrpc.getUser                        sample  228152   4.210 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.636           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.100           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.235           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.389           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.665           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.550           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.687           ms/op
ClientGrpc.listUser                       sample  173976   5.515 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.882           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.430           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.846           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.350           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.751           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.979           ms/op
