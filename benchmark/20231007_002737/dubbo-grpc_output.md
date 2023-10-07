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
# Warmup Iteration   1: 4.646 ops/ms
# Warmup Iteration   2: 8.662 ops/ms
# Warmup Iteration   3: 9.741 ops/ms
Iteration   1: 10.231 ops/ms
Iteration   2: 10.185 ops/ms
Iteration   3: 10.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.264 ±(99.9%) 1.824 ops/ms [Average]
  (min, avg, max) = (10.185, 10.264, 10.376), stdev = 0.100
  CI (99.9%): [8.440, 12.088] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 8.144 ops/ms
# Warmup Iteration   2: 10.541 ops/ms
# Warmup Iteration   3: 10.694 ops/ms
Iteration   1: 10.928 ops/ms
Iteration   2: 10.943 ops/ms
Iteration   3: 10.892 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.921 ±(99.9%) 0.480 ops/ms [Average]
  (min, avg, max) = (10.892, 10.921, 10.943), stdev = 0.026
  CI (99.9%): [10.441, 11.401] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 8.109 ops/ms
# Warmup Iteration   2: 9.856 ops/ms
# Warmup Iteration   3: 10.244 ops/ms
Iteration   1: 10.348 ops/ms
Iteration   2: 10.471 ops/ms
Iteration   3: 10.151 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.323 ±(99.9%) 2.948 ops/ms [Average]
  (min, avg, max) = (10.151, 10.323, 10.471), stdev = 0.162
  CI (99.9%): [7.375, 13.272] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.177 ops/ms
# Warmup Iteration   2: 7.954 ops/ms
# Warmup Iteration   3: 8.304 ops/ms
Iteration   1: 8.323 ops/ms
Iteration   2: 8.433 ops/ms
Iteration   3: 8.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.378 ±(99.9%) 1.002 ops/ms [Average]
  (min, avg, max) = (8.323, 8.378, 8.433), stdev = 0.055
  CI (99.9%): [7.375, 9.380] (assumes normal distribution)


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.004 ms/op
Iteration   1: 3.083 ±(99.9%) 0.009 ms/op
Iteration   2: 3.097 ±(99.9%) 0.004 ms/op
Iteration   3: 3.077 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.086 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (3.077, 3.086, 3.097), stdev = 0.010
  CI (99.9%): [2.899, 3.272] (assumes normal distribution)


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
# Warmup Iteration   1: 3.609 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 2.959 ±(99.9%) 0.004 ms/op
Iteration   2: 2.978 ±(99.9%) 0.004 ms/op
Iteration   3: 2.953 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.963 ±(99.9%) 0.237 ms/op [Average]
  (min, avg, max) = (2.953, 2.963, 2.978), stdev = 0.013
  CI (99.9%): [2.726, 3.201] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.191 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.004 ms/op
Iteration   1: 3.115 ±(99.9%) 0.005 ms/op
Iteration   2: 3.094 ±(99.9%) 0.009 ms/op
Iteration   3: 3.035 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.081 ±(99.9%) 0.755 ms/op [Average]
  (min, avg, max) = (3.035, 3.081, 3.115), stdev = 0.041
  CI (99.9%): [2.326, 3.836] (assumes normal distribution)


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
# Warmup Iteration   1: 4.513 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.036 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.019 ms/op
Iteration   1: 3.819 ±(99.9%) 0.024 ms/op
Iteration   2: 3.888 ±(99.9%) 0.050 ms/op
Iteration   3: 3.787 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.831 ±(99.9%) 0.942 ms/op [Average]
  (min, avg, max) = (3.787, 3.831, 3.888), stdev = 0.052
  CI (99.9%): [2.889, 4.773] (assumes normal distribution)


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
# Warmup Iteration   1: 4.363 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.508 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  16.407 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.708 ms/op

Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  11.256 ms/op
                 createUser·p0.9999: 23.396 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.575 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.949 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311694
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16368 
    [ 2.500,  5.000) = 293688 
    [ 5.000,  7.500) = 1248 
    [ 7.500, 10.000) = 74 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =     11.141 ms/op
     p(99.9900) =     23.364 ms/op
     p(99.9990) =     24.048 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.545 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  8.634 ms/op
                 existUser·p0.9999: 11.338 ms/op
                 existUser·p1.00:   11.698 ms/op

Iteration   2: 2.977 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.739 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.429 ms/op
                 existUser·p0.999:  9.462 ms/op
                 existUser·p0.9999: 23.953 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.584 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.784 ms/op
                 existUser·p0.9999: 16.543 ms/op
                 existUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320555
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30575 
    [ 2.500,  5.000) = 288418 
    [ 5.000,  7.500) = 1065 
    [ 7.500, 10.000) = 253 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     24.183 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 4.081 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.006 ms/op
Iteration   1: 3.030 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.785 ms/op
                 getUser·p0.9999: 15.816 ms/op
                 getUser·p1.00:   20.021 ms/op

Iteration   2: 3.089 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  9.631 ms/op
                 getUser·p0.9999: 15.428 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.728 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  9.596 ms/op
                 getUser·p0.9999: 24.137 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313241
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14187 
    [ 2.500,  5.000) = 297559 
    [ 5.000,  7.500) = 915 
    [ 7.500, 10.000) = 298 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      9.413 ms/op
     p(99.9900) =     22.600 ms/op
     p(99.9990) =     25.096 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 5.369 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.010 ms/op
Iteration   1: 3.853 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.896 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  12.154 ms/op
                 listUser·p0.9999: 20.644 ms/op
                 listUser·p1.00:   25.690 ms/op

Iteration   2: 3.784 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.251 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  12.976 ms/op
                 listUser·p0.9999: 16.085 ms/op
                 listUser·p1.00:   16.466 ms/op

Iteration   3: 3.870 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.397 ms/op
                 listUser·p0.9999: 16.588 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250327
  mean =      3.835 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4217 
    [ 2.500,  5.000) = 231425 
    [ 5.000,  7.500) = 13632 
    [ 7.500, 10.000) = 560 
    [10.000, 12.500) = 205 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.124 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     20.726 ms/op
     p(99.9999) =     25.690 ms/op
    p(100.0000) =     25.690 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.264 ± 1.824  ops/ms
ClientGrpc.existUser                       thrpt       3  10.921 ± 0.480  ops/ms
ClientGrpc.getUser                         thrpt       3  10.323 ± 2.948  ops/ms
ClientGrpc.listUser                        thrpt       3   8.378 ± 1.002  ops/ms
ClientGrpc.createUser                       avgt       3   3.086 ± 0.187   ms/op
ClientGrpc.existUser                        avgt       3   2.963 ± 0.237   ms/op
ClientGrpc.getUser                          avgt       3   3.081 ± 0.755   ms/op
ClientGrpc.listUser                         avgt       3   3.831 ± 0.942   ms/op
ClientGrpc.createUser                     sample  311694   3.078 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.508           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.141           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.364           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.117           ms/op
ClientGrpc.existUser                      sample  320555   2.993 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.584           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.716           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.792           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.281           ms/op
ClientGrpc.getUser                        sample  313241   3.064 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.630           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.413           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.600           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.199           ms/op
ClientGrpc.listUser                       sample  250327   3.835 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.896           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.342           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.124           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.857           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.690           ms/op
