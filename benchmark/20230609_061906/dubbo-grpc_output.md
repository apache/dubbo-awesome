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
# Warmup Iteration   1: 3.907 ops/ms
# Warmup Iteration   2: 8.135 ops/ms
# Warmup Iteration   3: 10.079 ops/ms
Iteration   1: 10.384 ops/ms
Iteration   2: 10.309 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.382 ±(99.9%) 1.305 ops/ms [Average]
  (min, avg, max) = (10.309, 10.382, 10.452), stdev = 0.072
  CI (99.9%): [9.077, 11.686] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.992 ops/ms
# Warmup Iteration   2: 10.135 ops/ms
# Warmup Iteration   3: 10.950 ops/ms
Iteration   1: 10.767 ops/ms
Iteration   2: 10.631 ops/ms
Iteration   3: 10.673 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.690 ±(99.9%) 1.265 ops/ms [Average]
  (min, avg, max) = (10.631, 10.690, 10.767), stdev = 0.069
  CI (99.9%): [9.425, 11.955] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.363 ops/ms
# Warmup Iteration   2: 9.811 ops/ms
# Warmup Iteration   3: 10.272 ops/ms
Iteration   1: 10.251 ops/ms
Iteration   2: 10.259 ops/ms
Iteration   3: 10.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.187 ±(99.9%) 2.174 ops/ms [Average]
  (min, avg, max) = (10.049, 10.187, 10.259), stdev = 0.119
  CI (99.9%): [8.012, 12.361] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.967 ops/ms
# Warmup Iteration   2: 7.003 ops/ms
# Warmup Iteration   3: 7.633 ops/ms
Iteration   1: 7.544 ops/ms
Iteration   2: 7.653 ops/ms
Iteration   3: 7.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.632 ±(99.9%) 1.459 ops/ms [Average]
  (min, avg, max) = (7.544, 7.632, 7.699), stdev = 0.080
  CI (99.9%): [6.173, 9.091] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.578 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.003 ms/op
Iteration   1: 3.046 ±(99.9%) 0.003 ms/op
Iteration   2: 3.116 ±(99.9%) 0.001 ms/op
Iteration   3: 3.118 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.093 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (3.046, 3.093, 3.118), stdev = 0.041
  CI (99.9%): [2.348, 3.839] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.230 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.084 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.002 ms/op
Iteration   1: 2.951 ±(99.9%) 0.003 ms/op
Iteration   2: 2.926 ±(99.9%) 0.002 ms/op
Iteration   3: 2.960 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.946 ±(99.9%) 0.327 ms/op [Average]
  (min, avg, max) = (2.926, 2.946, 2.960), stdev = 0.018
  CI (99.9%): [2.618, 3.273] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.337 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.002 ms/op
Iteration   1: 3.129 ±(99.9%) 0.009 ms/op
Iteration   2: 3.183 ±(99.9%) 0.004 ms/op
Iteration   3: 3.043 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.118 ±(99.9%) 1.285 ms/op [Average]
  (min, avg, max) = (3.043, 3.118, 3.183), stdev = 0.070
  CI (99.9%): [1.834, 4.403] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.402 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.315 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.008 ms/op
Iteration   1: 4.076 ±(99.9%) 0.019 ms/op
Iteration   2: 4.102 ±(99.9%) 0.014 ms/op
Iteration   3: 4.204 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.127 ±(99.9%) 1.241 ms/op [Average]
  (min, avg, max) = (4.076, 4.127, 4.204), stdev = 0.068
  CI (99.9%): [2.886, 5.368] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.437 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
Iteration   1: 3.137 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.687 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  7.609 ms/op
                 createUser·p0.9999: 16.803 ms/op
                 createUser·p1.00:   17.072 ms/op

Iteration   2: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.182 ms/op
                 createUser·p0.999:  8.316 ms/op
                 createUser·p0.9999: 21.718 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.654 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  9.204 ms/op
                 createUser·p0.9999: 22.957 ms/op
                 createUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310778
  mean =      3.089 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12756 
    [ 2.500,  5.000) = 296552 
    [ 5.000,  7.500) = 1104 
    [ 7.500, 10.000) = 132 
    [10.000, 12.500) = 10 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.930 ms/op
     p(99.9900) =     22.378 ms/op
     p(99.9990) =     23.291 ms/op
     p(99.9999) =     23.921 ms/op
    p(100.0000) =     23.921 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.274 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.004 ms/op
Iteration   1: 2.915 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.903 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.256 ms/op
                 existUser·p0.95:   3.379 ms/op
                 existUser·p0.99:   3.809 ms/op
                 existUser·p0.999:  5.489 ms/op
                 existUser·p0.9999: 12.190 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   2: 2.961 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  6.603 ms/op
                 existUser·p0.9999: 18.258 ms/op
                 existUser·p1.00:   18.547 ms/op

Iteration   3: 2.937 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.729 ms/op
                 existUser·p0.9999: 16.564 ms/op
                 existUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326745
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 855 
    [ 1.250,  2.500) = 20458 
    [ 2.500,  3.750) = 297969 
    [ 3.750,  5.000) = 6311 
    [ 5.000,  6.250) = 752 
    [ 6.250,  7.500) = 227 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      6.539 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.431 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.308 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.242 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  12.124 ms/op
                 getUser·p0.9999: 13.486 ms/op
                 getUser·p1.00:   13.910 ms/op

Iteration   2: 3.160 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  6.835 ms/op
                 getUser·p0.9999: 21.787 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   3: 3.211 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  8.067 ms/op
                 getUser·p0.9999: 18.324 ms/op
                 getUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299478
  mean =      3.204 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9472 
    [ 2.500,  5.000) = 288190 
    [ 5.000,  7.500) = 1444 
    [ 7.500, 10.000) = 148 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      8.077 ms/op
     p(99.9900) =     21.106 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 5.479 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.514 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.010 ±(99.9%) 0.012 ms/op
Iteration   1: 4.239 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.257 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.389 ms/op
                 listUser·p0.999:  14.893 ms/op
                 listUser·p0.9999: 22.297 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   2: 4.298 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   4.096 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.259 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 18.270 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 4.325 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   4.125 ms/op
                 listUser·p0.90:   5.439 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.644 ms/op
                 listUser·p0.999:  15.764 ms/op
                 listUser·p0.9999: 24.496 ms/op
                 listUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 223939
  mean =      4.287 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1132 
    [ 2.500,  5.000) = 190616 
    [ 5.000,  7.500) = 29934 
    [ 7.500, 10.000) = 1701 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.110 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      6.070 ms/op
     p(99.0000) =      7.509 ms/op
     p(99.9000) =     15.255 ms/op
     p(99.9900) =     22.677 ms/op
     p(99.9990) =     25.175 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.382 ± 1.305  ops/ms
ClientGrpc.existUser                       thrpt       3  10.690 ± 1.265  ops/ms
ClientGrpc.getUser                         thrpt       3  10.187 ± 2.174  ops/ms
ClientGrpc.listUser                        thrpt       3   7.632 ± 1.459  ops/ms
ClientGrpc.createUser                       avgt       3   3.093 ± 0.746   ms/op
ClientGrpc.existUser                        avgt       3   2.946 ± 0.327   ms/op
ClientGrpc.getUser                          avgt       3   3.118 ± 1.285   ms/op
ClientGrpc.listUser                         avgt       3   4.127 ± 1.241   ms/op
ClientGrpc.createUser                     sample  310778   3.089 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.654           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.930           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.378           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.921           ms/op
ClientGrpc.existUser                      sample  326745   2.938 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.771           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.539           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.022           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.547           ms/op
ClientGrpc.getUser                        sample  299478   3.204 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.764           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.166           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.985           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.678           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.077           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.106           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  223939   4.287 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.110           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.092           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.070           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.509           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.255           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.677           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.199           ms/op
