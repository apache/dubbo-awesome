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
# Warmup Iteration   1: 4.237 ops/ms
# Warmup Iteration   2: 9.060 ops/ms
# Warmup Iteration   3: 10.077 ops/ms
Iteration   1: 10.394 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.437 ±(99.9%) 0.742 ops/ms [Average]
  (min, avg, max) = (10.394, 10.437, 10.474), stdev = 0.041
  CI (99.9%): [9.695, 11.179] (assumes normal distribution)


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
# Warmup Iteration   1: 7.358 ops/ms
# Warmup Iteration   2: 10.334 ops/ms
# Warmup Iteration   3: 10.972 ops/ms
Iteration   1: 10.672 ops/ms
Iteration   2: 10.958 ops/ms
Iteration   3: 10.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.809 ±(99.9%) 2.609 ops/ms [Average]
  (min, avg, max) = (10.672, 10.809, 10.958), stdev = 0.143
  CI (99.9%): [8.200, 13.418] (assumes normal distribution)


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
# Warmup Iteration   1: 6.931 ops/ms
# Warmup Iteration   2: 10.192 ops/ms
# Warmup Iteration   3: 10.462 ops/ms
Iteration   1: 10.287 ops/ms
Iteration   2: 10.465 ops/ms
Iteration   3: 10.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.504 ±(99.9%) 4.366 ops/ms [Average]
  (min, avg, max) = (10.287, 10.504, 10.760), stdev = 0.239
  CI (99.9%): [6.138, 14.869] (assumes normal distribution)


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
# Warmup Iteration   1: 5.475 ops/ms
# Warmup Iteration   2: 7.966 ops/ms
# Warmup Iteration   3: 8.151 ops/ms
Iteration   1: 8.028 ops/ms
Iteration   2: 8.187 ops/ms
Iteration   3: 8.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.155 ±(99.9%) 2.071 ops/ms [Average]
  (min, avg, max) = (8.028, 8.155, 8.249), stdev = 0.114
  CI (99.9%): [6.083, 10.226] (assumes normal distribution)


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
# Warmup Iteration   1: 4.351 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.211 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.001 ms/op
Iteration   1: 3.099 ±(99.9%) 0.004 ms/op
Iteration   2: 3.098 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.094 ±(99.9%) 0.154 ms/op [Average]
  (min, avg, max) = (3.084, 3.094, 3.099), stdev = 0.008
  CI (99.9%): [2.939, 3.248] (assumes normal distribution)


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.160 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.002 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 2.917 ±(99.9%) 0.002 ms/op
Iteration   3: 2.851 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.916 ±(99.9%) 1.175 ms/op [Average]
  (min, avg, max) = (2.851, 2.916, 2.980), stdev = 0.064
  CI (99.9%): [1.742, 4.091] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.337 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.002 ms/op
Iteration   1: 3.059 ±(99.9%) 0.001 ms/op
Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
Iteration   3: 3.103 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (3.051, 3.071, 3.103), stdev = 0.028
  CI (99.9%): [2.555, 3.587] (assumes normal distribution)


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
# Warmup Iteration   1: 4.797 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.009 ms/op
Iteration   1: 3.903 ±(99.9%) 0.028 ms/op
Iteration   2: 3.816 ±(99.9%) 0.019 ms/op
Iteration   3: 3.845 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.854 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.816, 3.854, 3.903), stdev = 0.044
  CI (99.9%): [3.045, 4.664] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.006 ms/op
Iteration   1: 3.110 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  7.907 ms/op
                 createUser·p0.9999: 20.504 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   5.030 ms/op
                 createUser·p0.999:  8.751 ms/op
                 createUser·p0.9999: 22.728 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 3.140 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  13.418 ms/op
                 createUser·p0.9999: 24.518 ms/op
                 createUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308515
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17063 
    [ 2.500,  5.000) = 288267 
    [ 5.000,  7.500) = 2521 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.030 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     23.172 ms/op
     p(99.9990) =     25.155 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 3.841 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.918 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  5.987 ms/op
                 existUser·p0.9999: 11.940 ms/op
                 existUser·p1.00:   12.665 ms/op

Iteration   2: 2.923 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.242 ms/op
                 existUser·p0.9999: 13.976 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.421 ms/op
                 existUser·p0.9999: 15.307 ms/op
                 existUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326638
  mean =      2.937 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1002 
    [ 1.250,  2.500) = 39373 
    [ 2.500,  3.750) = 276816 
    [ 3.750,  5.000) = 7709 
    [ 5.000,  6.250) = 957 
    [ 6.250,  7.500) = 405 
    [ 7.500,  8.750) = 197 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.712 ms/op
     p(99.9900) =     15.030 ms/op
     p(99.9990) =     15.470 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.982 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  10.283 ms/op
                 getUser·p0.9999: 12.739 ms/op
                 getUser·p1.00:   12.894 ms/op

Iteration   2: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.936 ms/op
                 getUser·p0.999:  7.633 ms/op
                 getUser·p0.9999: 15.410 ms/op
                 getUser·p1.00:   15.794 ms/op

Iteration   3: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.759 ms/op
                 getUser·p0.9999: 16.746 ms/op
                 getUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313591
  mean =      3.063 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 13276 
    [ 2.500,  3.750) = 285381 
    [ 3.750,  5.000) = 12193 
    [ 5.000,  6.250) = 1436 
    [ 6.250,  7.500) = 550 
    [ 7.500,  8.750) = 208 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 88 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.801 ms/op
     p(99.9000) =      9.336 ms/op
     p(99.9900) =     16.220 ms/op
     p(99.9990) =     16.932 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 5.141 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.010 ms/op
Iteration   1: 3.958 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.933 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 21.348 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 3.959 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.910 ms/op
                 listUser·p0.9999: 19.028 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.858 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  14.371 ms/op
                 listUser·p0.9999: 15.822 ms/op
                 listUser·p1.00:   16.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244590
  mean =      3.924 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2183 
    [ 2.500,  5.000) = 227790 
    [ 5.000,  7.500) = 13406 
    [ 7.500, 10.000) = 654 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 162 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.276 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     21.711 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.437 ± 0.742  ops/ms
ClientGrpc.existUser                       thrpt       3  10.809 ± 2.609  ops/ms
ClientGrpc.getUser                         thrpt       3  10.504 ± 4.366  ops/ms
ClientGrpc.listUser                        thrpt       3   8.155 ± 2.071  ops/ms
ClientGrpc.createUser                       avgt       3   3.094 ± 0.154   ms/op
ClientGrpc.existUser                        avgt       3   2.916 ± 1.175   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 0.516   ms/op
ClientGrpc.listUser                         avgt       3   3.854 ± 0.809   ms/op
ClientGrpc.createUser                     sample  308515   3.110 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.653           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.030           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.503           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.172           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.395           ms/op
ClientGrpc.existUser                      sample  326638   2.937 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.737           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.712           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.030           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.614           ms/op
ClientGrpc.getUser                        sample  313591   3.063 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.823           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.518           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.801           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.336           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.220           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.072           ms/op
ClientGrpc.listUser                       sample  244590   3.924 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.761           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.276           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.185           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.823           ms/op
