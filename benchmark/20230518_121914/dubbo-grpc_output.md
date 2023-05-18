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
# Warmup Iteration   1: 3.936 ops/ms
# Warmup Iteration   2: 8.143 ops/ms
# Warmup Iteration   3: 9.772 ops/ms
Iteration   1: 10.126 ops/ms
Iteration   2: 10.174 ops/ms
Iteration   3: 10.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.226 ±(99.9%) 2.453 ops/ms [Average]
  (min, avg, max) = (10.126, 10.226, 10.379), stdev = 0.134
  CI (99.9%): [7.773, 12.679] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.783 ops/ms
# Warmup Iteration   2: 10.356 ops/ms
# Warmup Iteration   3: 10.734 ops/ms
Iteration   1: 10.692 ops/ms
Iteration   2: 10.530 ops/ms
Iteration   3: 10.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.489 ±(99.9%) 4.111 ops/ms [Average]
  (min, avg, max) = (10.247, 10.489, 10.692), stdev = 0.225
  CI (99.9%): [6.379, 14.600] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.688 ops/ms
# Warmup Iteration   2: 8.770 ops/ms
# Warmup Iteration   3: 9.873 ops/ms
Iteration   1: 10.337 ops/ms
Iteration   2: 10.846 ops/ms
Iteration   3: 10.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.597 ±(99.9%) 4.646 ops/ms [Average]
  (min, avg, max) = (10.337, 10.597, 10.846), stdev = 0.255
  CI (99.9%): [5.952, 15.243] (assumes normal distribution)


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
# Warmup Iteration   1: 5.904 ops/ms
# Warmup Iteration   2: 7.535 ops/ms
# Warmup Iteration   3: 7.589 ops/ms
Iteration   1: 7.945 ops/ms
Iteration   2: 7.700 ops/ms
Iteration   3: 8.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.885 ±(99.9%) 2.988 ops/ms [Average]
  (min, avg, max) = (7.700, 7.885, 8.011), stdev = 0.164
  CI (99.9%): [4.897, 10.873] (assumes normal distribution)


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
# Warmup Iteration   1: 3.800 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.002 ms/op
Iteration   1: 3.080 ±(99.9%) 0.002 ms/op
Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.043 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.007, 3.043, 3.080), stdev = 0.037
  CI (99.9%): [2.377, 3.710] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.003 ms/op
Iteration   1: 2.928 ±(99.9%) 0.003 ms/op
Iteration   2: 2.887 ±(99.9%) 0.003 ms/op
Iteration   3: 2.859 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (2.859, 2.891, 2.928), stdev = 0.035
  CI (99.9%): [2.256, 3.526] (assumes normal distribution)


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
# Warmup Iteration   1: 4.069 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.004 ms/op
Iteration   1: 3.134 ±(99.9%) 0.002 ms/op
Iteration   2: 3.206 ±(99.9%) 0.002 ms/op
Iteration   3: 3.063 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.134 ±(99.9%) 1.303 ms/op [Average]
  (min, avg, max) = (3.063, 3.134, 3.206), stdev = 0.071
  CI (99.9%): [1.831, 4.437] (assumes normal distribution)


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
# Warmup Iteration   1: 4.569 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.890 ±(99.9%) 0.020 ms/op
Iteration   1: 3.919 ±(99.9%) 0.026 ms/op
Iteration   2: 4.017 ±(99.9%) 0.021 ms/op
Iteration   3: 3.967 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.968 ±(99.9%) 0.893 ms/op [Average]
  (min, avg, max) = (3.919, 3.968, 4.017), stdev = 0.049
  CI (99.9%): [3.075, 4.861] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.890 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.957 ±(99.9%) 0.007 ms/op
Iteration   1: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.652 ms/op
                 createUser·p0.9999: 16.600 ms/op
                 createUser·p1.00:   17.465 ms/op

Iteration   2: 3.004 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.496 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  14.100 ms/op
                 createUser·p0.9999: 16.515 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   3: 3.237 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  8.294 ms/op
                 createUser·p0.9999: 18.136 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312205
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1671 
    [ 1.250,  2.500) = 26726 
    [ 2.500,  3.750) = 260752 
    [ 3.750,  5.000) = 21638 
    [ 5.000,  6.250) = 802 
    [ 6.250,  7.500) = 188 
    [ 7.500,  8.750) = 89 
    [ 8.750, 10.000) = 78 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 94 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      9.303 ms/op
     p(99.9900) =     16.663 ms/op
     p(99.9990) =     18.735 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.946 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.005 ms/op
Iteration   1: 2.791 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.643 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.539 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.774 ms/op
                 existUser·p0.9999: 21.972 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 2.801 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.527 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  9.792 ms/op
                 existUser·p0.9999: 22.675 ms/op
                 existUser·p1.00:   23.101 ms/op

Iteration   3: 2.863 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.482 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  5.956 ms/op
                 existUser·p0.9999: 16.411 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340555
  mean =      2.818 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56956 
    [ 2.500,  5.000) = 282723 
    [ 5.000,  7.500) = 568 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.922 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.944 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.007 ms/op
Iteration   1: 3.033 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.503 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.174 ms/op
                 getUser·p0.999:  6.853 ms/op
                 getUser·p0.9999: 18.758 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   2: 2.967 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.521 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 19.282 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   3: 3.050 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.071 ms/op
                 getUser·p0.9999: 31.999 ms/op
                 getUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318003
  mean =      3.017 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23789 
    [ 2.500,  5.000) = 293247 
    [ 5.000,  7.500) = 729 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.947 ms/op
     p(99.9900) =     30.559 ms/op
     p(99.9990) =     32.375 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


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
# Warmup Iteration   1: 4.979 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.010 ms/op
Iteration   1: 3.957 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.912 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  11.668 ms/op
                 listUser·p0.9999: 13.283 ms/op
                 listUser·p1.00:   13.566 ms/op

Iteration   2: 3.917 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 19.093 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   3: 4.000 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.572 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  18.315 ms/op
                 listUser·p0.9999: 27.223 ms/op
                 listUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242573
  mean =      3.958 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5575 
    [ 2.500,  5.000) = 212083 
    [ 5.000,  7.500) = 23646 
    [ 7.500, 10.000) = 760 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     14.729 ms/op
     p(99.9900) =     25.756 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.226 ± 2.453  ops/ms
ClientGrpc.existUser                       thrpt       3  10.489 ± 4.111  ops/ms
ClientGrpc.getUser                         thrpt       3  10.597 ± 4.646  ops/ms
ClientGrpc.listUser                        thrpt       3   7.885 ± 2.988  ops/ms
ClientGrpc.createUser                       avgt       3   3.043 ± 0.666   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 0.635   ms/op
ClientGrpc.getUser                          avgt       3   3.134 ± 1.303   ms/op
ClientGrpc.listUser                         avgt       3   3.968 ± 0.893   ms/op
ClientGrpc.createUser                     sample  312205   3.072 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.496           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.303           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.663           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.842           ms/op
ClientGrpc.existUser                      sample  340555   2.818 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.482           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.289           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.922           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.053           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.101           ms/op
ClientGrpc.getUser                        sample  318003   3.017 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.503           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.736           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.947           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.559           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.440           ms/op
ClientGrpc.listUser                       sample  242573   3.958 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.572           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.729           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.756           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.443           ms/op
