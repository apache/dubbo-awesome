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
# Warmup Iteration   1: 2.285 ops/ms
# Warmup Iteration   2: 5.402 ops/ms
# Warmup Iteration   3: 6.949 ops/ms
Iteration   1: 7.234 ops/ms
Iteration   2: 7.337 ops/ms
Iteration   3: 7.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.420 ±(99.9%) 4.378 ops/ms [Average]
  (min, avg, max) = (7.234, 7.420, 7.691), stdev = 0.240
  CI (99.9%): [3.043, 11.798] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.264 ops/ms
# Warmup Iteration   2: 7.648 ops/ms
# Warmup Iteration   3: 7.983 ops/ms
Iteration   1: 8.264 ops/ms
Iteration   2: 8.282 ops/ms
Iteration   3: 7.867 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.138 ±(99.9%) 4.276 ops/ms [Average]
  (min, avg, max) = (7.867, 8.138, 8.282), stdev = 0.234
  CI (99.9%): [3.862, 12.414] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.149 ops/ms
# Warmup Iteration   2: 6.594 ops/ms
# Warmup Iteration   3: 7.158 ops/ms
Iteration   1: 8.051 ops/ms
Iteration   2: 7.678 ops/ms
Iteration   3: 7.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.751 ±(99.9%) 4.939 ops/ms [Average]
  (min, avg, max) = (7.524, 7.751, 8.051), stdev = 0.271
  CI (99.9%): [2.812, 12.690] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.913 ops/ms
# Warmup Iteration   2: 5.429 ops/ms
# Warmup Iteration   3: 6.122 ops/ms
Iteration   1: 6.010 ops/ms
Iteration   2: 5.762 ops/ms
Iteration   3: 5.840 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.871 ±(99.9%) 2.310 ops/ms [Average]
  (min, avg, max) = (5.762, 5.871, 6.010), stdev = 0.127
  CI (99.9%): [3.561, 8.181] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.633 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.769 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.503 ±(99.9%) 0.009 ms/op
Iteration   1: 4.346 ±(99.9%) 0.005 ms/op
Iteration   2: 4.209 ±(99.9%) 0.003 ms/op
Iteration   3: 4.190 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.248 ±(99.9%) 1.556 ms/op [Average]
  (min, avg, max) = (4.190, 4.248, 4.346), stdev = 0.085
  CI (99.9%): [2.692, 5.805] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.446 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.003 ms/op
Iteration   1: 4.077 ±(99.9%) 0.003 ms/op
Iteration   2: 4.054 ±(99.9%) 0.003 ms/op
Iteration   3: 4.158 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.096 ±(99.9%) 1.000 ms/op [Average]
  (min, avg, max) = (4.054, 4.096, 4.158), stdev = 0.055
  CI (99.9%): [3.096, 5.096] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 5.601 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.630 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.420 ±(99.9%) 0.004 ms/op
Iteration   1: 4.384 ±(99.9%) 0.004 ms/op
Iteration   2: 4.366 ±(99.9%) 0.005 ms/op
Iteration   3: 4.346 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.365 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (4.346, 4.365, 4.384), stdev = 0.019
  CI (99.9%): [4.014, 4.717] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.180 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.688 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.536 ±(99.9%) 0.023 ms/op
Iteration   1: 5.205 ±(99.9%) 0.011 ms/op
Iteration   2: 5.408 ±(99.9%) 0.020 ms/op
Iteration   3: 5.626 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.413 ±(99.9%) 3.844 ms/op [Average]
  (min, avg, max) = (5.205, 5.413, 5.626), stdev = 0.211
  CI (99.9%): [1.569, 9.257] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.983 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.602 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.357 ±(99.9%) 0.014 ms/op
Iteration   1: 4.152 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   4.022 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  10.931 ms/op
                 createUser·p0.9999: 18.149 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 4.164 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   4.059 ms/op
                 createUser·p0.90:   5.226 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  14.107 ms/op
                 createUser·p0.9999: 18.481 ms/op
                 createUser·p1.00:   19.005 ms/op

Iteration   3: 4.072 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   4.997 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   7.455 ms/op
                 createUser·p0.999:  13.344 ms/op
                 createUser·p0.9999: 20.031 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 232586
  mean =      4.129 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4548 
    [ 2.500,  5.000) = 198274 
    [ 5.000,  7.500) = 27599 
    [ 7.500, 10.000) = 1689 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      4.006 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     18.768 ms/op
     p(99.9990) =     20.405 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.504 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.439 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.437 ±(99.9%) 0.012 ms/op
Iteration   1: 4.486 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.198 ms/op
                 existUser·p0.50:   4.325 ms/op
                 existUser·p0.90:   5.661 ms/op
                 existUser·p0.95:   6.185 ms/op
                 existUser·p0.99:   8.258 ms/op
                 existUser·p0.999:  13.655 ms/op
                 existUser·p0.9999: 16.378 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   2: 4.166 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.628 ms/op
                 existUser·p0.99:   7.135 ms/op
                 existUser·p0.999:  12.849 ms/op
                 existUser·p0.9999: 30.233 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 4.156 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   4.014 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   7.487 ms/op
                 existUser·p0.999:  12.452 ms/op
                 existUser·p0.9999: 20.546 ms/op
                 existUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 224988
  mean =      4.264 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3542 
    [ 2.500,  5.000) = 184580 
    [ 5.000,  7.500) = 34386 
    [ 7.500, 10.000) = 1743 
    [10.000, 12.500) = 420 
    [12.500, 15.000) = 218 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      4.121 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     13.206 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     30.523 ms/op
     p(99.9999) =     30.605 ms/op
    p(100.0000) =     30.605 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.455 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.591 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.012 ms/op
Iteration   1: 4.196 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.100 ms/op
                 getUser·p0.90:   5.243 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  12.403 ms/op
                 getUser·p0.9999: 15.872 ms/op
                 getUser·p1.00:   16.204 ms/op

Iteration   2: 4.181 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   4.055 ms/op
                 getUser·p0.90:   5.259 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  11.089 ms/op
                 getUser·p0.9999: 20.372 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   3: 4.238 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   4.129 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   7.766 ms/op
                 getUser·p0.999:  12.125 ms/op
                 getUser·p0.9999: 20.524 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 228235
  mean =      4.205 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4307 
    [ 2.500,  5.000) = 189404 
    [ 5.000,  7.500) = 32557 
    [ 7.500, 10.000) = 1520 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     12.091 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     20.953 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


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
# Warmup Iteration   1: 7.357 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.950 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.312 ±(99.9%) 0.022 ms/op
Iteration   1: 5.348 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   4.964 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.438 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 27.266 ms/op
                 listUser·p1.00:   27.853 ms/op

Iteration   2: 5.221 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   7.168 ms/op
                 listUser·p0.95:   8.086 ms/op
                 listUser·p0.99:   10.338 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 22.659 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 5.096 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  18.523 ms/op
                 listUser·p0.9999: 27.034 ms/op
                 listUser·p1.00:   28.180 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 183941
  mean =      5.220 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 725 
    [ 2.500,  5.000) = 99514 
    [ 5.000,  7.500) = 67957 
    [ 7.500, 10.000) = 13349 
    [10.000, 12.500) = 1702 
    [12.500, 15.000) = 336 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.208 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      7.291 ms/op
     p(95.0000) =      8.184 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     19.007 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     27.905 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.420 ± 4.378  ops/ms
ClientGrpc.existUser                       thrpt       3   8.138 ± 4.276  ops/ms
ClientGrpc.getUser                         thrpt       3   7.751 ± 4.939  ops/ms
ClientGrpc.listUser                        thrpt       3   5.871 ± 2.310  ops/ms
ClientGrpc.createUser                       avgt       3   4.248 ± 1.556   ms/op
ClientGrpc.existUser                        avgt       3   4.096 ± 1.000   ms/op
ClientGrpc.getUser                          avgt       3   4.365 ± 0.352   ms/op
ClientGrpc.listUser                         avgt       3   5.413 ± 3.844   ms/op
ClientGrpc.createUser                     sample  232586   4.129 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.784           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.628           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.373           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.025           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.768           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.365           ms/op
ClientGrpc.existUser                      sample  224988   4.264 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.825           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.358           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.857           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.635           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.206           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.017           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.605           ms/op
ClientGrpc.getUser                        sample  228235   4.205 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.752           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.726           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.266           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.091           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.218           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.872           ms/op
ClientGrpc.listUser                       sample  183941   5.220 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.208           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.291           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.184           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.420           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.001           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.180           ms/op
