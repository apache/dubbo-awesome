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
# Warmup Iteration   1: 4.051 ops/ms
# Warmup Iteration   2: 9.054 ops/ms
# Warmup Iteration   3: 9.768 ops/ms
Iteration   1: 10.316 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.289 ±(99.9%) 1.250 ops/ms [Average]
  (min, avg, max) = (10.212, 10.289, 10.341), stdev = 0.069
  CI (99.9%): [9.039, 11.540] (assumes normal distribution)


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
# Warmup Iteration   1: 7.291 ops/ms
# Warmup Iteration   2: 10.141 ops/ms
# Warmup Iteration   3: 10.779 ops/ms
Iteration   1: 11.119 ops/ms
Iteration   2: 11.137 ops/ms
Iteration   3: 11.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.130 ±(99.9%) 0.182 ops/ms [Average]
  (min, avg, max) = (11.119, 11.130, 11.137), stdev = 0.010
  CI (99.9%): [10.948, 11.313] (assumes normal distribution)


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
# Warmup Iteration   1: 6.748 ops/ms
# Warmup Iteration   2: 10.154 ops/ms
# Warmup Iteration   3: 10.507 ops/ms
Iteration   1: 10.487 ops/ms
Iteration   2: 10.754 ops/ms
Iteration   3: 10.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.610 ±(99.9%) 2.462 ops/ms [Average]
  (min, avg, max) = (10.487, 10.610, 10.754), stdev = 0.135
  CI (99.9%): [8.148, 13.073] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.769 ops/ms
# Warmup Iteration   2: 7.829 ops/ms
# Warmup Iteration   3: 7.849 ops/ms
Iteration   1: 7.837 ops/ms
Iteration   2: 8.049 ops/ms
Iteration   3: 7.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.946 ±(99.9%) 1.931 ops/ms [Average]
  (min, avg, max) = (7.837, 7.946, 8.049), stdev = 0.106
  CI (99.9%): [6.015, 9.877] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.422 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.003 ms/op
Iteration   1: 3.038 ±(99.9%) 0.002 ms/op
Iteration   2: 3.053 ±(99.9%) 0.004 ms/op
Iteration   3: 3.030 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.040 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (3.030, 3.040, 3.053), stdev = 0.012
  CI (99.9%): [2.825, 3.256] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.002 ms/op
Iteration   1: 2.915 ±(99.9%) 0.003 ms/op
Iteration   2: 2.903 ±(99.9%) 0.002 ms/op
Iteration   3: 2.930 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.916 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (2.903, 2.916, 2.930), stdev = 0.013
  CI (99.9%): [2.676, 3.156] (assumes normal distribution)


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 3.069 ±(99.9%) 0.004 ms/op
Iteration   3: 3.093 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.079 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.069, 3.079, 3.093), stdev = 0.012
  CI (99.9%): [2.862, 3.296] (assumes normal distribution)


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
# Warmup Iteration   1: 4.838 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.100 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.023 ms/op
Iteration   1: 4.006 ±(99.9%) 0.015 ms/op
Iteration   2: 4.072 ±(99.9%) 0.010 ms/op
Iteration   3: 4.020 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.032 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (4.006, 4.032, 4.072), stdev = 0.035
  CI (99.9%): [3.398, 4.667] (assumes normal distribution)


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
# Warmup Iteration   1: 4.459 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.007 ms/op
Iteration   1: 3.093 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.605 ms/op
                 createUser·p0.999:  7.783 ms/op
                 createUser·p0.9999: 24.335 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.021 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.890 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   4.149 ms/op
                 createUser·p0.999:  9.315 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   3: 3.025 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.616 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.677 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  11.895 ms/op
                 createUser·p0.9999: 22.081 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315054
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18740 
    [ 2.500,  5.000) = 294695 
    [ 5.000,  7.500) = 1170 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      9.534 ms/op
     p(99.9900) =     22.855 ms/op
     p(99.9990) =     24.445 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 3.958 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.894 ±(99.9%) 0.007 ms/op
Iteration   1: 2.989 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.119 ms/op
                 existUser·p0.9999: 13.423 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   2: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.148 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   23.069 ms/op

Iteration   3: 2.940 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  11.339 ms/op
                 existUser·p0.9999: 29.760 ms/op
                 existUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326115
  mean =      2.943 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38240 
    [ 2.500,  5.000) = 286575 
    [ 5.000,  7.500) = 1002 
    [ 7.500, 10.000) = 42 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.209 ms/op
     p(99.9900) =     25.372 ms/op
     p(99.9990) =     30.261 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


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
# Warmup Iteration   1: 4.319 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  6.601 ms/op
                 getUser·p0.9999: 15.245 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  8.205 ms/op
                 getUser·p0.9999: 14.415 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.405 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315088
  mean =      3.044 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20274 
    [ 2.500,  5.000) = 293250 
    [ 5.000,  7.500) = 1261 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     22.314 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 5.063 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.085 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.012 ms/op
Iteration   1: 4.034 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  14.926 ms/op
                 listUser·p0.9999: 21.596 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 4.010 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.665 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  16.536 ms/op
                 listUser·p0.9999: 19.992 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.000 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.254 ms/op
                 listUser·p0.9999: 18.775 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239196
  mean =      4.015 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2135 
    [ 2.500,  5.000) = 214397 
    [ 5.000,  7.500) = 21293 
    [ 7.500, 10.000) = 946 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     21.138 ms/op
     p(99.9990) =     21.831 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.289 ± 1.250  ops/ms
ClientGrpc.existUser                       thrpt       3  11.130 ± 0.182  ops/ms
ClientGrpc.getUser                         thrpt       3  10.610 ± 2.462  ops/ms
ClientGrpc.listUser                        thrpt       3   7.946 ± 1.931  ops/ms
ClientGrpc.createUser                       avgt       3   3.040 ± 0.216   ms/op
ClientGrpc.existUser                        avgt       3   2.916 ± 0.240   ms/op
ClientGrpc.getUser                          avgt       3   3.079 ± 0.217   ms/op
ClientGrpc.listUser                         avgt       3   4.032 ± 0.635   ms/op
ClientGrpc.createUser                     sample  315054   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.616           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.534           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.855           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.543           ms/op
ClientGrpc.existUser                      sample  326115   2.943 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.705           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.209           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.372           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.343           ms/op
ClientGrpc.getUser                        sample  315088   3.044 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.607           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.531           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.406           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.314           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.035           ms/op
ClientGrpc.listUser                       sample  239196   4.015 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.665           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.303           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.138           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.282           ms/op
