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
# Warmup Iteration   1: 2.440 ops/ms
# Warmup Iteration   2: 5.504 ops/ms
# Warmup Iteration   3: 7.393 ops/ms
Iteration   1: 7.341 ops/ms
Iteration   2: 7.393 ops/ms
Iteration   3: 7.449 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.394 ±(99.9%) 0.985 ops/ms [Average]
  (min, avg, max) = (7.341, 7.394, 7.449), stdev = 0.054
  CI (99.9%): [6.409, 8.379] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.291 ops/ms
# Warmup Iteration   2: 7.522 ops/ms
# Warmup Iteration   3: 8.078 ops/ms
Iteration   1: 7.895 ops/ms
Iteration   2: 8.619 ops/ms
Iteration   3: 8.516 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.343 ±(99.9%) 7.147 ops/ms [Average]
  (min, avg, max) = (7.895, 8.343, 8.619), stdev = 0.392
  CI (99.9%): [1.196, 15.491] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.140 ops/ms
# Warmup Iteration   2: 6.741 ops/ms
# Warmup Iteration   3: 7.700 ops/ms
Iteration   1: 7.828 ops/ms
Iteration   2: 7.862 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.910 ±(99.9%) 2.081 ops/ms [Average]
  (min, avg, max) = (7.828, 7.910, 8.040), stdev = 0.114
  CI (99.9%): [5.830, 9.991] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.707 ops/ms
# Warmup Iteration   2: 5.455 ops/ms
# Warmup Iteration   3: 5.950 ops/ms
Iteration   1: 5.815 ops/ms
Iteration   2: 6.081 ops/ms
Iteration   3: 6.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.081 ±(99.9%) 4.856 ops/ms [Average]
  (min, avg, max) = (5.815, 6.081, 6.347), stdev = 0.266
  CI (99.9%): [1.225, 10.937] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.971 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.276 ±(99.9%) 0.004 ms/op
Iteration   1: 4.334 ±(99.9%) 0.004 ms/op
Iteration   2: 4.313 ±(99.9%) 0.006 ms/op
Iteration   3: 4.210 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.285 ±(99.9%) 1.214 ms/op [Average]
  (min, avg, max) = (4.210, 4.285, 4.334), stdev = 0.067
  CI (99.9%): [3.071, 5.499] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.724 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.005 ms/op
Iteration   1: 4.080 ±(99.9%) 0.003 ms/op
Iteration   2: 4.176 ±(99.9%) 0.003 ms/op
Iteration   3: 3.970 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.075 ±(99.9%) 1.876 ms/op [Average]
  (min, avg, max) = (3.970, 4.075, 4.176), stdev = 0.103
  CI (99.9%): [2.200, 5.951] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.877 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.158 ±(99.9%) 0.002 ms/op
Iteration   1: 4.291 ±(99.9%) 0.002 ms/op
Iteration   2: 4.281 ±(99.9%) 0.003 ms/op
Iteration   3: 4.320 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.297 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (4.281, 4.297, 4.320), stdev = 0.020
  CI (99.9%): [3.928, 4.667] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.900 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.472 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.226 ±(99.9%) 0.011 ms/op
Iteration   1: 4.969 ±(99.9%) 0.011 ms/op
Iteration   2: 5.073 ±(99.9%) 0.013 ms/op
Iteration   3: 5.061 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.034 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (4.969, 5.034, 5.073), stdev = 0.057
  CI (99.9%): [3.995, 6.074] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.058 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.598 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.013 ms/op
Iteration   1: 4.215 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.204 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.161 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   7.684 ms/op
                 createUser·p0.999:  10.883 ms/op
                 createUser·p0.9999: 19.215 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   2: 4.175 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   7.396 ms/op
                 createUser·p0.999:  13.890 ms/op
                 createUser·p0.9999: 21.474 ms/op
                 createUser·p1.00:   22.151 ms/op

Iteration   3: 4.018 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.524 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.743 ms/op
                 createUser·p0.95:   5.145 ms/op
                 createUser·p0.99:   6.729 ms/op
                 createUser·p0.999:  13.810 ms/op
                 createUser·p0.9999: 19.169 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 232091
  mean =      4.134 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3547 
    [ 2.500,  5.000) = 204335 
    [ 5.000,  7.500) = 22228 
    [ 7.500, 10.000) = 1412 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.524 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     13.067 ms/op
     p(99.9900) =     19.909 ms/op
     p(99.9990) =     21.969 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 5.898 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.332 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.015 ms/op
Iteration   1: 3.951 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   3.863 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   7.259 ms/op
                 existUser·p0.999:  12.173 ms/op
                 existUser·p0.9999: 19.333 ms/op
                 existUser·p1.00:   19.726 ms/op

Iteration   2: 3.983 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.382 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  12.545 ms/op
                 existUser·p0.9999: 16.073 ms/op
                 existUser·p1.00:   17.957 ms/op

Iteration   3: 4.069 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.969 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.578 ms/op
                 existUser·p0.999:  13.681 ms/op
                 existUser·p0.9999: 24.431 ms/op
                 existUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 239876
  mean =      4.000 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9100 
    [ 2.500,  5.000) = 205557 
    [ 5.000,  7.500) = 23322 
    [ 7.500, 10.000) = 1160 
    [10.000, 12.500) = 457 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     12.782 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     25.028 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.893 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.083 ±(99.9%) 0.011 ms/op
Iteration   1: 4.269 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   4.182 ms/op
                 getUser·p0.90:   5.325 ms/op
                 getUser·p0.95:   5.652 ms/op
                 getUser·p0.99:   7.069 ms/op
                 getUser·p0.999:  10.848 ms/op
                 getUser·p0.9999: 14.795 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   2: 4.332 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.685 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  10.715 ms/op
                 getUser·p0.9999: 14.884 ms/op
                 getUser·p1.00:   15.843 ms/op

Iteration   3: 4.157 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.943 ms/op
                 getUser·p0.50:   4.063 ms/op
                 getUser·p0.90:   5.169 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   7.037 ms/op
                 getUser·p0.999:  11.669 ms/op
                 getUser·p0.9999: 19.704 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225684
  mean =      4.252 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3571 
    [ 2.500,  5.000) = 182762 
    [ 5.000,  7.500) = 37766 
    [ 7.500, 10.000) = 1180 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      4.166 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      6.833 ms/op
     p(99.9000) =     11.015 ms/op
     p(99.9900) =     19.380 ms/op
     p(99.9990) =     20.160 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 7.400 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.281 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.954 ±(99.9%) 0.017 ms/op
Iteration   1: 5.173 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   6.693 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.795 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 18.967 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 5.125 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   4.915 ms/op
                 listUser·p0.90:   6.382 ms/op
                 listUser·p0.95:   7.258 ms/op
                 listUser·p0.99:   9.516 ms/op
                 listUser·p0.999:  18.435 ms/op
                 listUser·p0.9999: 23.276 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   3: 5.028 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   7.315 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  19.038 ms/op
                 listUser·p0.9999: 21.615 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 187828
  mean =      5.108 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 347 
    [ 2.500,  5.000) = 103397 
    [ 5.000,  7.500) = 75721 
    [ 7.500, 10.000) = 6982 
    [10.000, 12.500) = 874 
    [12.500, 15.000) = 182 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.373 ms/op
     p(99.0000) =      9.486 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     23.871 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.394 ± 0.985  ops/ms
ClientGrpc.existUser                       thrpt       3   8.343 ± 7.147  ops/ms
ClientGrpc.getUser                         thrpt       3   7.910 ± 2.081  ops/ms
ClientGrpc.listUser                        thrpt       3   6.081 ± 4.856  ops/ms
ClientGrpc.createUser                       avgt       3   4.285 ± 1.214   ms/op
ClientGrpc.existUser                        avgt       3   4.075 ± 1.876   ms/op
ClientGrpc.getUser                          avgt       3   4.297 ± 0.369   ms/op
ClientGrpc.listUser                         avgt       3   5.034 ± 1.039   ms/op
ClientGrpc.createUser                     sample  232091   4.134 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.524           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.022           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.030           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.464           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.234           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.067           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.909           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.151           ms/op
ClientGrpc.existUser                      sample  239876   4.000 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.820           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.038           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.464           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.021           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.782           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.823           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.199           ms/op
ClientGrpc.getUser                        sample  225684   4.252 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.685           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.166           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.333           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.015           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.380           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.283           ms/op
ClientGrpc.listUser                       sample  187828   5.108 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.153           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.529           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.373           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.486           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.924           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.660           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.986           ms/op
