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
# Warmup Iteration   1: 2.605 ops/ms
# Warmup Iteration   2: 5.877 ops/ms
# Warmup Iteration   3: 7.327 ops/ms
Iteration   1: 7.455 ops/ms
Iteration   2: 7.475 ops/ms
Iteration   3: 7.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.430 ±(99.9%) 1.109 ops/ms [Average]
  (min, avg, max) = (7.361, 7.430, 7.475), stdev = 0.061
  CI (99.9%): [6.321, 8.540] (assumes normal distribution)


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
# Warmup Iteration   1: 4.521 ops/ms
# Warmup Iteration   2: 7.474 ops/ms
# Warmup Iteration   3: 8.071 ops/ms
Iteration   1: 8.511 ops/ms
Iteration   2: 8.172 ops/ms
Iteration   3: 8.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.362 ±(99.9%) 3.157 ops/ms [Average]
  (min, avg, max) = (8.172, 8.362, 8.511), stdev = 0.173
  CI (99.9%): [5.205, 11.519] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ops/ms
# Warmup Iteration   2: 6.815 ops/ms
# Warmup Iteration   3: 7.102 ops/ms
Iteration   1: 7.203 ops/ms
Iteration   2: 7.442 ops/ms
Iteration   3: 7.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.302 ±(99.9%) 2.281 ops/ms [Average]
  (min, avg, max) = (7.203, 7.302, 7.442), stdev = 0.125
  CI (99.9%): [5.020, 9.583] (assumes normal distribution)


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
# Warmup Iteration   1: 3.676 ops/ms
# Warmup Iteration   2: 4.987 ops/ms
# Warmup Iteration   3: 5.694 ops/ms
Iteration   1: 5.683 ops/ms
Iteration   2: 6.152 ops/ms
Iteration   3: 6.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.960 ±(99.9%) 4.482 ops/ms [Average]
  (min, avg, max) = (5.683, 5.960, 6.152), stdev = 0.246
  CI (99.9%): [1.478, 10.442] (assumes normal distribution)


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
# Warmup Iteration   1: 5.980 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.224 ±(99.9%) 0.008 ms/op
Iteration   1: 4.064 ±(99.9%) 0.004 ms/op
Iteration   2: 4.183 ±(99.9%) 0.007 ms/op
Iteration   3: 4.232 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.160 ±(99.9%) 1.569 ms/op [Average]
  (min, avg, max) = (4.064, 4.160, 4.232), stdev = 0.086
  CI (99.9%): [2.591, 5.729] (assumes normal distribution)


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
# Warmup Iteration   1: 5.961 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.120 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.002 ms/op
Iteration   1: 3.922 ±(99.9%) 0.008 ms/op
Iteration   2: 3.976 ±(99.9%) 0.006 ms/op
Iteration   3: 3.963 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.954 ±(99.9%) 0.511 ms/op [Average]
  (min, avg, max) = (3.922, 3.954, 3.976), stdev = 0.028
  CI (99.9%): [3.442, 4.465] (assumes normal distribution)


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
# Warmup Iteration   1: 6.105 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.545 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.416 ±(99.9%) 0.005 ms/op
Iteration   1: 4.329 ±(99.9%) 0.006 ms/op
Iteration   2: 4.305 ±(99.9%) 0.008 ms/op
Iteration   3: 4.248 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.294 ±(99.9%) 0.763 ms/op [Average]
  (min, avg, max) = (4.248, 4.294, 4.329), stdev = 0.042
  CI (99.9%): [3.531, 5.056] (assumes normal distribution)


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
# Warmup Iteration   1: 7.955 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.587 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.440 ±(99.9%) 0.029 ms/op
Iteration   1: 5.351 ±(99.9%) 0.014 ms/op
Iteration   2: 5.190 ±(99.9%) 0.035 ms/op
Iteration   3: 5.079 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.207 ±(99.9%) 2.490 ms/op [Average]
  (min, avg, max) = (5.079, 5.207, 5.351), stdev = 0.136
  CI (99.9%): [2.717, 7.696] (assumes normal distribution)


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
# Warmup Iteration   1: 6.619 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.011 ms/op
Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  13.795 ms/op
                 createUser·p0.9999: 17.874 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   2: 4.114 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.231 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   5.128 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   6.472 ms/op
                 createUser·p0.999:  8.719 ms/op
                 createUser·p0.9999: 20.490 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   3: 4.210 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   4.112 ms/op
                 createUser·p0.90:   5.243 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  16.941 ms/op
                 createUser·p0.9999: 21.837 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 234157
  mean =      4.099 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5015 
    [ 2.500,  5.000) = 198984 
    [ 5.000,  7.500) = 28857 
    [ 7.500, 10.000) = 792 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      4.002 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     15.057 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     22.456 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 5.067 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.075 ±(99.9%) 0.012 ms/op
Iteration   1: 3.925 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.874 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.581 ms/op
                 existUser·p0.999:  10.732 ms/op
                 existUser·p0.9999: 23.424 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   2: 3.903 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.899 ms/op
                 existUser·p0.95:   5.251 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  10.420 ms/op
                 existUser·p0.9999: 15.850 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   3: 3.826 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.760 ms/op
                 existUser·p0.90:   4.694 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   6.545 ms/op
                 existUser·p0.999:  15.932 ms/op
                 existUser·p0.9999: 20.311 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247004
  mean =      3.884 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7475 
    [ 2.500,  5.000) = 220994 
    [ 5.000,  7.500) = 17258 
    [ 7.500, 10.000) = 870 
    [10.000, 12.500) = 165 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.785 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     12.353 ms/op
     p(99.9900) =     20.074 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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
# Warmup Iteration   1: 6.364 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.432 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.429 ±(99.9%) 0.015 ms/op
Iteration   1: 4.191 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   4.092 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.546 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  11.085 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.068 ms/op

Iteration   2: 4.315 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.431 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  10.599 ms/op
                 getUser·p0.9999: 17.072 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   3: 4.183 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.096 ms/op
                 getUser·p0.50:   4.088 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   6.541 ms/op
                 getUser·p0.999:  13.872 ms/op
                 getUser·p0.9999: 22.370 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 227065
  mean =      4.229 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1837 
    [ 2.500,  5.000) = 190555 
    [ 5.000,  7.500) = 33226 
    [ 7.500, 10.000) = 1068 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     11.125 ms/op
     p(99.9900) =     23.940 ms/op
     p(99.9990) =     25.008 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 8.170 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 5.712 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.164 ±(99.9%) 0.017 ms/op
Iteration   1: 5.247 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.868 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.324 ms/op
                 listUser·p0.95:   7.381 ms/op
                 listUser·p0.99:   10.085 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 18.926 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 5.201 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.579 ms/op
                 listUser·p0.50:   4.981 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.553 ms/op
                 listUser·p0.99:   10.338 ms/op
                 listUser·p0.999:  17.138 ms/op
                 listUser·p0.9999: 20.311 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   3: 5.464 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.091 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   6.881 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  20.856 ms/op
                 listUser·p0.9999: 27.424 ms/op
                 listUser·p1.00:   29.032 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 181012
  mean =      5.301 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 150 
    [ 2.500,  5.000) = 82528 
    [ 5.000,  7.500) = 88808 
    [ 7.500, 10.000) = 7595 
    [10.000, 12.500) = 1248 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 162 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.579 ms/op
     p(50.0000) =      5.087 ms/op
     p(90.0000) =      6.570 ms/op
     p(95.0000) =      7.586 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     26.771 ms/op
     p(99.9990) =     28.979 ms/op
     p(99.9999) =     29.032 ms/op
    p(100.0000) =     29.032 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.430 ± 1.109  ops/ms
ClientGrpc.existUser                       thrpt       3   8.362 ± 3.157  ops/ms
ClientGrpc.getUser                         thrpt       3   7.302 ± 2.281  ops/ms
ClientGrpc.listUser                        thrpt       3   5.960 ± 4.482  ops/ms
ClientGrpc.createUser                       avgt       3   4.160 ± 1.569   ms/op
ClientGrpc.existUser                        avgt       3   3.954 ± 0.511   ms/op
ClientGrpc.getUser                          avgt       3   4.294 ± 0.763   ms/op
ClientGrpc.listUser                         avgt       3   5.207 ± 2.490   ms/op
ClientGrpc.createUser                     sample  234157   4.099 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.100           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.161           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.595           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.791           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.057           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.414           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.527           ms/op
ClientGrpc.existUser                      sample  247004   3.884 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.785           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.833           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.235           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.472           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.353           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.074           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.116           ms/op
ClientGrpc.getUser                        sample  227065   4.229 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.019           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.267           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.710           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.849           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.125           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.940           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.068           ms/op
ClientGrpc.listUser                       sample  181012   5.301 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.579           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.570           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.586           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.109           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.465           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.771           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.032           ms/op
