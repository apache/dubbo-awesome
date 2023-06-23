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
# Warmup Iteration   1: 4.439 ops/ms
# Warmup Iteration   2: 9.141 ops/ms
# Warmup Iteration   3: 10.416 ops/ms
Iteration   1: 10.601 ops/ms
Iteration   2: 10.717 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.650 ±(99.9%) 1.094 ops/ms [Average]
  (min, avg, max) = (10.601, 10.650, 10.717), stdev = 0.060
  CI (99.9%): [9.556, 11.745] (assumes normal distribution)


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
# Warmup Iteration   1: 8.129 ops/ms
# Warmup Iteration   2: 11.110 ops/ms
# Warmup Iteration   3: 11.257 ops/ms
Iteration   1: 11.383 ops/ms
Iteration   2: 11.232 ops/ms
Iteration   3: 11.376 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.331 ±(99.9%) 1.551 ops/ms [Average]
  (min, avg, max) = (11.232, 11.331, 11.383), stdev = 0.085
  CI (99.9%): [9.780, 12.882] (assumes normal distribution)


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
# Warmup Iteration   1: 7.931 ops/ms
# Warmup Iteration   2: 10.335 ops/ms
# Warmup Iteration   3: 10.513 ops/ms
Iteration   1: 10.735 ops/ms
Iteration   2: 10.647 ops/ms
Iteration   3: 10.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.655 ±(99.9%) 1.391 ops/ms [Average]
  (min, avg, max) = (10.583, 10.655, 10.735), stdev = 0.076
  CI (99.9%): [9.264, 12.046] (assumes normal distribution)


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
# Warmup Iteration   1: 6.528 ops/ms
# Warmup Iteration   2: 7.895 ops/ms
# Warmup Iteration   3: 8.167 ops/ms
Iteration   1: 8.320 ops/ms
Iteration   2: 8.251 ops/ms
Iteration   3: 8.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.284 ±(99.9%) 0.633 ops/ms [Average]
  (min, avg, max) = (8.251, 8.284, 8.320), stdev = 0.035
  CI (99.9%): [7.652, 8.917] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.002 ms/op
Iteration   1: 2.929 ±(99.9%) 0.003 ms/op
Iteration   2: 2.955 ±(99.9%) 0.004 ms/op
Iteration   3: 2.981 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.955 ±(99.9%) 0.476 ms/op [Average]
  (min, avg, max) = (2.929, 2.955, 2.981), stdev = 0.026
  CI (99.9%): [2.479, 3.431] (assumes normal distribution)


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.927 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.871 ±(99.9%) 0.003 ms/op
Iteration   1: 2.761 ±(99.9%) 0.005 ms/op
Iteration   2: 2.868 ±(99.9%) 0.005 ms/op
Iteration   3: 2.918 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.849 ±(99.9%) 1.460 ms/op [Average]
  (min, avg, max) = (2.761, 2.849, 2.918), stdev = 0.080
  CI (99.9%): [1.389, 4.309] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.933 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.002 ms/op
Iteration   1: 2.953 ±(99.9%) 0.003 ms/op
Iteration   2: 2.979 ±(99.9%) 0.003 ms/op
Iteration   3: 2.936 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.956 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.936, 2.956, 2.979), stdev = 0.021
  CI (99.9%): [2.566, 3.346] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.226 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.913 ±(99.9%) 0.018 ms/op
Iteration   1: 3.858 ±(99.9%) 0.011 ms/op
Iteration   2: 3.852 ±(99.9%) 0.006 ms/op
Iteration   3: 3.825 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.845 ±(99.9%) 0.321 ms/op [Average]
  (min, avg, max) = (3.825, 3.845, 3.858), stdev = 0.018
  CI (99.9%): [3.524, 4.166] (assumes normal distribution)


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.919 ms/op
                 createUser·p0.9999: 12.157 ms/op
                 createUser·p1.00:   12.370 ms/op

Iteration   2: 2.974 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.507 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.375 ms/op
                 createUser·p0.95:   3.543 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  7.903 ms/op
                 createUser·p0.9999: 12.951 ms/op
                 createUser·p1.00:   13.238 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  12.959 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321982
  mean =      2.981 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28317 
    [ 2.500,  5.000) = 292620 
    [ 5.000,  7.500) = 683 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.332 ms/op
     p(99.9900) =     20.478 ms/op
     p(99.9990) =     22.792 ms/op
     p(99.9999) =     33.817 ms/op
    p(100.0000) =     33.817 ms/op


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
# Warmup Iteration   1: 3.838 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.927 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.006 ms/op
Iteration   1: 2.891 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.446 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.450 ms/op
                 existUser·p0.9999: 11.501 ms/op
                 existUser·p1.00:   11.682 ms/op

Iteration   2: 2.857 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.534 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  6.103 ms/op
                 existUser·p0.9999: 12.370 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   3: 2.846 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.230 ms/op
                 existUser·p0.9999: 15.270 ms/op
                 existUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335155
  mean =      2.865 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2257 
    [ 1.250,  2.500) = 46980 
    [ 2.500,  3.750) = 276309 
    [ 3.750,  5.000) = 8553 
    [ 5.000,  6.250) = 724 
    [ 6.250,  7.500) = 97 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.387 ms/op
     p(95.0000) =      3.596 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.193 ms/op
     p(99.9900) =     14.532 ms/op
     p(99.9990) =     15.477 ms/op
     p(99.9999) =     15.565 ms/op
    p(100.0000) =     15.565 ms/op


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
# Warmup Iteration   1: 3.678 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.005 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  7.553 ms/op
                 getUser·p0.9999: 13.884 ms/op
                 getUser·p1.00:   14.057 ms/op

Iteration   2: 2.967 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.713 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.359 ms/op
                 getUser·p0.95:   3.539 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  8.285 ms/op
                 getUser·p0.9999: 14.792 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.996 ms/op
                 getUser·p0.9999: 26.608 ms/op
                 getUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321893
  mean =      2.982 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26745 
    [ 2.500,  5.000) = 293623 
    [ 5.000,  7.500) = 1187 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.586 ms/op
     p(99.9900) =     24.131 ms/op
     p(99.9990) =     26.732 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 5.350 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.943 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.853 ±(99.9%) 0.010 ms/op
Iteration   1: 3.835 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.210 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  11.689 ms/op
                 listUser·p0.9999: 13.778 ms/op
                 listUser·p1.00:   14.385 ms/op

Iteration   2: 3.855 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.433 ms/op
                 listUser·p0.9999: 18.045 ms/op
                 listUser·p1.00:   18.416 ms/op

Iteration   3: 3.832 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  14.716 ms/op
                 listUser·p0.9999: 18.174 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250261
  mean =      3.841 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 6119 
    [ 2.500,  3.750) = 128970 
    [ 3.750,  5.000) = 95064 
    [ 5.000,  6.250) = 15650 
    [ 6.250,  7.500) = 3472 
    [ 7.500,  8.750) = 429 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.950 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.760 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     18.366 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.650 ± 1.094  ops/ms
ClientGrpc.existUser                       thrpt       3  11.331 ± 1.551  ops/ms
ClientGrpc.getUser                         thrpt       3  10.655 ± 1.391  ops/ms
ClientGrpc.listUser                        thrpt       3   8.284 ± 0.633  ops/ms
ClientGrpc.createUser                       avgt       3   2.955 ± 0.476   ms/op
ClientGrpc.existUser                        avgt       3   2.849 ± 1.460   ms/op
ClientGrpc.getUser                          avgt       3   2.956 ± 0.390   ms/op
ClientGrpc.listUser                         avgt       3   3.845 ± 0.321   ms/op
ClientGrpc.createUser                     sample  321982   2.981 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.507           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.453           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.332           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.478           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.817           ms/op
ClientGrpc.existUser                      sample  335155   2.865 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.446           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.193           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.532           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.565           ms/op
ClientGrpc.getUser                        sample  321893   2.982 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.713           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.966           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.469           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.586           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.131           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.771           ms/op
ClientGrpc.listUser                       sample  250261   3.841 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.950           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.760           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.074           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.022           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.416           ms/op
