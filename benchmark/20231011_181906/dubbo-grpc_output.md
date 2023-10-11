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
# Warmup Iteration   2: 4.995 ops/ms
# Warmup Iteration   3: 6.814 ops/ms
Iteration   1: 7.303 ops/ms
Iteration   2: 7.286 ops/ms
Iteration   3: 7.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.278 ±(99.9%) 0.525 ops/ms [Average]
  (min, avg, max) = (7.247, 7.278, 7.303), stdev = 0.029
  CI (99.9%): [6.754, 7.803] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.783 ops/ms
# Warmup Iteration   2: 7.911 ops/ms
# Warmup Iteration   3: 8.070 ops/ms
Iteration   1: 8.143 ops/ms
Iteration   2: 8.095 ops/ms
Iteration   3: 8.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.147 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (8.095, 8.147, 8.204), stdev = 0.055
  CI (99.9%): [7.147, 9.148] (assumes normal distribution)


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
# Warmup Iteration   1: 4.395 ops/ms
# Warmup Iteration   2: 7.217 ops/ms
# Warmup Iteration   3: 7.817 ops/ms
Iteration   1: 7.724 ops/ms
Iteration   2: 7.465 ops/ms
Iteration   3: 7.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.500 ±(99.9%) 3.812 ops/ms [Average]
  (min, avg, max) = (7.311, 7.500, 7.724), stdev = 0.209
  CI (99.9%): [3.688, 11.312] (assumes normal distribution)


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
# Warmup Iteration   1: 3.437 ops/ms
# Warmup Iteration   2: 5.132 ops/ms
# Warmup Iteration   3: 5.397 ops/ms
Iteration   1: 5.592 ops/ms
Iteration   2: 5.753 ops/ms
Iteration   3: 5.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.687 ±(99.9%) 1.541 ops/ms [Average]
  (min, avg, max) = (5.592, 5.687, 5.753), stdev = 0.084
  CI (99.9%): [4.145, 7.228] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.088 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.009 ms/op
Iteration   1: 4.378 ±(99.9%) 0.006 ms/op
Iteration   2: 4.348 ±(99.9%) 0.006 ms/op
Iteration   3: 4.328 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.352 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (4.328, 4.352, 4.378), stdev = 0.025
  CI (99.9%): [3.893, 4.810] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.386 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.384 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.078 ±(99.9%) 0.003 ms/op
Iteration   1: 3.999 ±(99.9%) 0.004 ms/op
Iteration   2: 3.794 ±(99.9%) 0.004 ms/op
Iteration   3: 3.743 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.845 ±(99.9%) 2.472 ms/op [Average]
  (min, avg, max) = (3.743, 3.845, 3.999), stdev = 0.135
  CI (99.9%): [1.374, 6.317] (assumes normal distribution)


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
# Warmup Iteration   1: 6.707 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.745 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.371 ±(99.9%) 0.011 ms/op
Iteration   1: 4.284 ±(99.9%) 0.004 ms/op
Iteration   2: 4.251 ±(99.9%) 0.006 ms/op
Iteration   3: 4.211 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.249 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (4.211, 4.249, 4.284), stdev = 0.037
  CI (99.9%): [3.580, 4.917] (assumes normal distribution)


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
# Warmup Iteration   1: 8.833 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 6.003 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.497 ±(99.9%) 0.022 ms/op
Iteration   1: 5.414 ±(99.9%) 0.030 ms/op
Iteration   2: 5.484 ±(99.9%) 0.021 ms/op
Iteration   3: 5.265 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.388 ±(99.9%) 2.048 ms/op [Average]
  (min, avg, max) = (5.265, 5.388, 5.484), stdev = 0.112
  CI (99.9%): [3.340, 7.435] (assumes normal distribution)


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
# Warmup Iteration   1: 7.153 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 4.843 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.351 ±(99.9%) 0.014 ms/op
Iteration   1: 4.286 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   4.157 ms/op
                 createUser·p0.90:   5.448 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   7.717 ms/op
                 createUser·p0.999:  15.914 ms/op
                 createUser·p0.9999: 20.382 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   2: 4.146 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.985 ms/op
                 createUser·p0.50:   3.985 ms/op
                 createUser·p0.90:   5.358 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   8.151 ms/op
                 createUser·p0.999:  14.120 ms/op
                 createUser·p0.9999: 23.357 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   3: 4.217 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   4.071 ms/op
                 createUser·p0.90:   5.333 ms/op
                 createUser·p0.95:   5.841 ms/op
                 createUser·p0.99:   8.012 ms/op
                 createUser·p0.999:  14.682 ms/op
                 createUser·p0.9999: 32.876 ms/op
                 createUser·p1.00:   34.472 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227644
  mean =      4.216 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6750 
    [ 2.500,  5.000) = 182920 
    [ 5.000,  7.500) = 35042 
    [ 7.500, 10.000) = 1913 
    [10.000, 12.500) = 601 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      4.071 ms/op
     p(90.0000) =      5.382 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     14.555 ms/op
     p(99.9900) =     32.211 ms/op
     p(99.9990) =     33.387 ms/op
     p(99.9999) =     34.472 ms/op
    p(100.0000) =     34.472 ms/op


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
# Warmup Iteration   1: 6.218 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.013 ms/op
Iteration   1: 4.145 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.957 ms/op
                 existUser·p0.90:   5.308 ms/op
                 existUser·p0.95:   5.956 ms/op
                 existUser·p0.99:   8.389 ms/op
                 existUser·p0.999:  12.693 ms/op
                 existUser·p0.9999: 16.323 ms/op
                 existUser·p1.00:   21.430 ms/op

Iteration   2: 4.322 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   4.055 ms/op
                 existUser·p0.90:   5.784 ms/op
                 existUser·p0.95:   6.657 ms/op
                 existUser·p0.99:   8.929 ms/op
                 existUser·p0.999:  15.467 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   21.463 ms/op

Iteration   3: 3.918 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.850 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   7.340 ms/op
                 existUser·p0.999:  16.351 ms/op
                 existUser·p0.9999: 28.760 ms/op
                 existUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 232725
  mean =      4.122 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7316 
    [ 2.500,  5.000) = 193386 
    [ 5.000,  7.500) = 27965 
    [ 7.500, 10.000) = 3197 
    [10.000, 12.500) = 506 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.038 ms/op
     p(99.0000) =      8.331 ms/op
     p(99.9000) =     14.542 ms/op
     p(99.9900) =     25.747 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.166 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.688 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.259 ±(99.9%) 0.012 ms/op
Iteration   1: 4.372 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   4.170 ms/op
                 getUser·p0.90:   5.644 ms/op
                 getUser·p0.95:   6.357 ms/op
                 getUser·p0.99:   8.913 ms/op
                 getUser·p0.999:  14.350 ms/op
                 getUser·p0.9999: 24.153 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   2: 4.380 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   4.153 ms/op
                 getUser·p0.90:   5.685 ms/op
                 getUser·p0.95:   6.513 ms/op
                 getUser·p0.99:   9.322 ms/op
                 getUser·p0.999:  18.218 ms/op
                 getUser·p0.9999: 28.269 ms/op
                 getUser·p1.00:   28.410 ms/op

Iteration   3: 4.487 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.931 ms/op
                 getUser·p0.50:   4.293 ms/op
                 getUser·p0.90:   5.685 ms/op
                 getUser·p0.95:   6.291 ms/op
                 getUser·p0.99:   8.667 ms/op
                 getUser·p0.999:  14.197 ms/op
                 getUser·p0.9999: 19.053 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217539
  mean =      4.412 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4508 
    [ 2.500,  5.000) = 165331 
    [ 5.000,  7.500) = 42950 
    [ 7.500, 10.000) = 3436 
    [10.000, 12.500) = 722 
    [12.500, 15.000) = 348 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      4.202 ms/op
     p(90.0000) =      5.677 ms/op
     p(95.0000) =      6.390 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     15.474 ms/op
     p(99.9900) =     27.861 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 8.388 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 5.948 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.416 ±(99.9%) 0.021 ms/op
Iteration   1: 5.328 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.610 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   6.963 ms/op
                 listUser·p0.95:   8.102 ms/op
                 listUser·p0.99:   10.682 ms/op
                 listUser·p0.999:  17.169 ms/op
                 listUser·p0.9999: 37.126 ms/op
                 listUser·p1.00:   42.467 ms/op

Iteration   2: 5.604 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   5.145 ms/op
                 listUser·p0.90:   7.840 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   12.465 ms/op
                 listUser·p0.999:  24.015 ms/op
                 listUser·p0.9999: 39.275 ms/op
                 listUser·p1.00:   46.203 ms/op

Iteration   3: 5.676 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   5.120 ms/op
                 listUser·p0.90:   8.126 ms/op
                 listUser·p0.95:   9.535 ms/op
                 listUser·p0.99:   13.156 ms/op
                 listUser·p0.999:  22.577 ms/op
                 listUser·p0.9999: 28.326 ms/op
                 listUser·p1.00:   43.713 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173502
  mean =      5.532 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 80307 
    [ 5.000, 10.000) = 88305 
    [10.000, 15.000) = 4265 
    [15.000, 20.000) = 402 
    [20.000, 25.000) = 122 
    [25.000, 30.000) = 57 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 36 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      5.095 ms/op
     p(90.0000) =      7.676 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     12.288 ms/op
     p(99.9000) =     22.167 ms/op
     p(99.9900) =     37.614 ms/op
     p(99.9990) =     46.107 ms/op
     p(99.9999) =     46.203 ms/op
    p(100.0000) =     46.203 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.278 ± 0.525  ops/ms
ClientGrpc.existUser                       thrpt       3   8.147 ± 1.000  ops/ms
ClientGrpc.getUser                         thrpt       3   7.500 ± 3.812  ops/ms
ClientGrpc.listUser                        thrpt       3   5.687 ± 1.541  ops/ms
ClientGrpc.createUser                       avgt       3   4.352 ± 0.458   ms/op
ClientGrpc.existUser                        avgt       3   3.845 ± 2.472   ms/op
ClientGrpc.getUser                          avgt       3   4.249 ± 0.668   ms/op
ClientGrpc.listUser                         avgt       3   5.388 ± 2.048   ms/op
ClientGrpc.createUser                     sample  227644   4.216 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.936           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.382           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.865           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.946           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.555           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.211           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.472           ms/op
ClientGrpc.existUser                      sample  232725   4.122 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.758           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.924           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.300           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.038           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.331           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          14.542           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.747           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.229           ms/op
ClientGrpc.getUser                        sample  217539   4.412 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.660           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.677           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.390           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.962           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.474           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.861           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.410           ms/op
ClientGrpc.listUser                       sample  173502   5.532 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.317           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.676           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.897           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.288           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          22.167           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          37.614           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          46.203           ms/op
