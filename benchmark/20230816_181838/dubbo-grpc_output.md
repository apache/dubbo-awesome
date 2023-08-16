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
# Warmup Iteration   1: 3.869 ops/ms
# Warmup Iteration   2: 8.516 ops/ms
# Warmup Iteration   3: 9.877 ops/ms
Iteration   1: 10.327 ops/ms
Iteration   2: 10.031 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.272 ±(99.9%) 3.985 ops/ms [Average]
  (min, avg, max) = (10.031, 10.272, 10.458), stdev = 0.218
  CI (99.9%): [6.286, 14.257] (assumes normal distribution)


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
# Warmup Iteration   1: 7.132 ops/ms
# Warmup Iteration   2: 10.517 ops/ms
# Warmup Iteration   3: 10.786 ops/ms
Iteration   1: 10.969 ops/ms
Iteration   2: 10.740 ops/ms
Iteration   3: 10.927 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.879 ±(99.9%) 2.221 ops/ms [Average]
  (min, avg, max) = (10.740, 10.879, 10.969), stdev = 0.122
  CI (99.9%): [8.658, 13.099] (assumes normal distribution)


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
# Warmup Iteration   1: 6.402 ops/ms
# Warmup Iteration   2: 10.082 ops/ms
# Warmup Iteration   3: 10.386 ops/ms
Iteration   1: 10.501 ops/ms
Iteration   2: 10.760 ops/ms
Iteration   3: 10.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.553 ±(99.9%) 3.401 ops/ms [Average]
  (min, avg, max) = (10.399, 10.553, 10.760), stdev = 0.186
  CI (99.9%): [7.153, 13.954] (assumes normal distribution)


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
# Warmup Iteration   1: 5.148 ops/ms
# Warmup Iteration   2: 7.580 ops/ms
# Warmup Iteration   3: 7.852 ops/ms
Iteration   1: 7.809 ops/ms
Iteration   2: 8.146 ops/ms
Iteration   3: 8.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.995 ±(99.9%) 3.131 ops/ms [Average]
  (min, avg, max) = (7.809, 7.995, 8.146), stdev = 0.172
  CI (99.9%): [4.864, 11.127] (assumes normal distribution)


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.290 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.003 ms/op
Iteration   1: 3.086 ±(99.9%) 0.005 ms/op
Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
Iteration   3: 3.057 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.079 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (3.057, 3.079, 3.095), stdev = 0.020
  CI (99.9%): [2.719, 3.440] (assumes normal distribution)


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
# Warmup Iteration   1: 4.070 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.145 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.003 ms/op
Iteration   1: 3.046 ±(99.9%) 0.003 ms/op
Iteration   2: 2.955 ±(99.9%) 0.002 ms/op
Iteration   3: 2.999 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.000 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (2.955, 3.000, 3.046), stdev = 0.045
  CI (99.9%): [2.171, 3.829] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.004 ms/op
Iteration   1: 3.134 ±(99.9%) 0.004 ms/op
Iteration   2: 3.064 ±(99.9%) 0.003 ms/op
Iteration   3: 3.075 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.091 ±(99.9%) 0.690 ms/op [Average]
  (min, avg, max) = (3.064, 3.091, 3.134), stdev = 0.038
  CI (99.9%): [2.401, 3.781] (assumes normal distribution)


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
# Warmup Iteration   1: 4.775 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.391 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.018 ms/op
Iteration   1: 4.066 ±(99.9%) 0.020 ms/op
Iteration   2: 4.032 ±(99.9%) 0.011 ms/op
Iteration   3: 4.023 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.041 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (4.023, 4.041, 4.066), stdev = 0.023
  CI (99.9%): [3.625, 4.456] (assumes normal distribution)


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
# Warmup Iteration   1: 4.441 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
Iteration   1: 3.089 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   5.243 ms/op
                 createUser·p0.999:  10.514 ms/op
                 createUser·p0.9999: 18.861 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  8.872 ms/op
                 createUser·p0.9999: 19.431 ms/op
                 createUser·p1.00:   19.661 ms/op

Iteration   3: 3.129 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  10.306 ms/op
                 createUser·p0.9999: 26.109 ms/op
                 createUser·p1.00:   26.378 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309151
  mean =      3.104 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15465 
    [ 2.500,  5.000) = 290299 
    [ 5.000,  7.500) = 2611 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.112 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     24.647 ms/op
     p(99.9990) =     26.310 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.002 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.007 ms/op
Iteration   1: 2.978 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  8.694 ms/op
                 existUser·p0.9999: 20.652 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 2.982 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.442 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  9.726 ms/op
                 existUser·p0.9999: 21.766 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   3: 2.940 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.816 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  8.186 ms/op
                 existUser·p0.9999: 29.626 ms/op
                 existUser·p1.00:   33.260 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323534
  mean =      2.967 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30312 
    [ 2.500,  5.000) = 289641 
    [ 5.000,  7.500) = 2876 
    [ 7.500, 10.000) = 462 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.442 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.404 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.112 ms/op
     p(99.9000) =      9.166 ms/op
     p(99.9900) =     26.623 ms/op
     p(99.9990) =     31.575 ms/op
     p(99.9999) =     33.260 ms/op
    p(100.0000) =     33.260 ms/op


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
# Warmup Iteration   1: 4.342 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.007 ms/op
Iteration   1: 3.079 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.460 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   5.136 ms/op
                 getUser·p0.999:  11.129 ms/op
                 getUser·p0.9999: 13.969 ms/op
                 getUser·p1.00:   14.205 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  9.601 ms/op
                 getUser·p0.9999: 16.980 ms/op
                 getUser·p1.00:   17.531 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.637 ms/op
                 getUser·p0.99:   4.799 ms/op
                 getUser·p0.999:  8.749 ms/op
                 getUser·p0.9999: 21.561 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312979
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16298 
    [ 2.500,  5.000) = 293415 
    [ 5.000,  7.500) = 2602 
    [ 7.500, 10.000) = 374 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.054 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     19.959 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


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
# Warmup Iteration   1: 5.217 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.282 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.128 ±(99.9%) 0.012 ms/op
Iteration   1: 4.091 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.087 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  15.663 ms/op
                 listUser·p0.9999: 20.087 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 4.068 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.349 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.568 ms/op
                 listUser·p0.999:  16.032 ms/op
                 listUser·p0.9999: 24.183 ms/op
                 listUser·p1.00:   25.166 ms/op

Iteration   3: 4.097 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.619 ms/op
                 listUser·p0.999:  17.690 ms/op
                 listUser·p0.9999: 25.139 ms/op
                 listUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 234998
  mean =      4.085 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3972 
    [ 2.500,  5.000) = 200184 
    [ 5.000,  7.500) = 28409 
    [ 7.500, 10.000) = 1795 
    [10.000, 12.500) = 210 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     16.138 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     26.064 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.272 ± 3.985  ops/ms
ClientGrpc.existUser                       thrpt       3  10.879 ± 2.221  ops/ms
ClientGrpc.getUser                         thrpt       3  10.553 ± 3.401  ops/ms
ClientGrpc.listUser                        thrpt       3   7.995 ± 3.131  ops/ms
ClientGrpc.createUser                       avgt       3   3.079 ± 0.360   ms/op
ClientGrpc.existUser                        avgt       3   3.000 ± 0.829   ms/op
ClientGrpc.getUser                          avgt       3   3.091 ± 0.690   ms/op
ClientGrpc.listUser                         avgt       3   4.041 ± 0.416   ms/op
ClientGrpc.createUser                     sample  309151   3.104 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.664           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.883           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.112           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.486           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.647           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.378           ms/op
ClientGrpc.existUser                      sample  323534   2.967 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.442           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.166           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.623           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.260           ms/op
ClientGrpc.getUser                        sample  312979   3.067 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.460           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.834           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.054           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.585           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.959           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.856           ms/op
ClientGrpc.listUser                       sample  234998   4.085 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.962           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.087           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.545           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.138           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.314           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.263           ms/op
