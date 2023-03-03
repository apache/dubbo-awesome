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
# Warmup Iteration   1: 4.511 ops/ms
# Warmup Iteration   2: 9.429 ops/ms
# Warmup Iteration   3: 10.631 ops/ms
Iteration   1: 10.610 ops/ms
Iteration   2: 10.367 ops/ms
Iteration   3: 10.316 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.431 ±(99.9%) 2.869 ops/ms [Average]
  (min, avg, max) = (10.316, 10.431, 10.610), stdev = 0.157
  CI (99.9%): [7.562, 13.300] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.787 ops/ms
# Warmup Iteration   2: 10.610 ops/ms
# Warmup Iteration   3: 11.036 ops/ms
Iteration   1: 10.824 ops/ms
Iteration   2: 10.755 ops/ms
Iteration   3: 10.722 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.767 ±(99.9%) 0.944 ops/ms [Average]
  (min, avg, max) = (10.722, 10.767, 10.824), stdev = 0.052
  CI (99.9%): [9.823, 11.711] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.934 ops/ms
# Warmup Iteration   2: 10.227 ops/ms
# Warmup Iteration   3: 10.297 ops/ms
Iteration   1: 10.414 ops/ms
Iteration   2: 10.153 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.365 ±(99.9%) 3.507 ops/ms [Average]
  (min, avg, max) = (10.153, 10.365, 10.529), stdev = 0.192
  CI (99.9%): [6.858, 13.873] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.814 ops/ms
# Warmup Iteration   2: 7.770 ops/ms
# Warmup Iteration   3: 7.928 ops/ms
Iteration   1: 8.192 ops/ms
Iteration   2: 8.233 ops/ms
Iteration   3: 7.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.073 ±(99.9%) 4.440 ops/ms [Average]
  (min, avg, max) = (7.793, 8.073, 8.233), stdev = 0.243
  CI (99.9%): [3.633, 12.512] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.070 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.002 ms/op
Iteration   1: 3.064 ±(99.9%) 0.003 ms/op
Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
Iteration   3: 3.046 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.057 ±(99.9%) 0.173 ms/op [Average]
  (min, avg, max) = (3.046, 3.057, 3.064), stdev = 0.009
  CI (99.9%): [2.884, 3.230] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.737 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.861 ±(99.9%) 0.004 ms/op
Iteration   1: 2.962 ±(99.9%) 0.002 ms/op
Iteration   2: 2.998 ±(99.9%) 0.002 ms/op
Iteration   3: 2.970 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.977 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (2.962, 2.977, 2.998), stdev = 0.019
  CI (99.9%): [2.629, 3.325] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.952 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.003 ms/op
Iteration   1: 2.968 ±(99.9%) 0.003 ms/op
Iteration   2: 2.991 ±(99.9%) 0.003 ms/op
Iteration   3: 2.986 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.982 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.968, 2.982, 2.991), stdev = 0.012
  CI (99.9%): [2.761, 3.202] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.437 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.014 ms/op
Iteration   1: 4.048 ±(99.9%) 0.019 ms/op
Iteration   2: 4.062 ±(99.9%) 0.019 ms/op
Iteration   3: 4.050 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.053 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (4.048, 4.053, 4.062), stdev = 0.008
  CI (99.9%): [3.914, 4.193] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.049 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.178 ms/op
                 createUser·p0.9999: 12.750 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   2: 3.204 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.572 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.741 ms/op
                 createUser·p0.9999: 13.927 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   3: 3.044 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  13.959 ms/op
                 createUser·p0.9999: 24.789 ms/op
                 createUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308897
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23562 
    [ 2.500,  5.000) = 284334 
    [ 5.000,  7.500) = 621 
    [ 7.500, 10.000) = 123 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.572 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.869 ms/op
     p(99.9900) =     23.283 ms/op
     p(99.9990) =     25.032 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.834 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.990 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.007 ms/op
Iteration   1: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  5.865 ms/op
                 existUser·p0.9999: 18.483 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  6.286 ms/op
                 existUser·p0.9999: 16.844 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.637 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  7.036 ms/op
                 existUser·p0.9999: 14.224 ms/op
                 existUser·p1.00:   14.598 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327494
  mean =      2.930 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2250 
    [ 1.250,  2.500) = 51069 
    [ 2.500,  3.750) = 257940 
    [ 3.750,  5.000) = 15640 
    [ 5.000,  6.250) = 292 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.111 ms/op
     p(99.9900) =     17.310 ms/op
     p(99.9990) =     18.791 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.625 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.007 ms/op
Iteration   1: 3.150 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.500 ms/op
                 getUser·p0.999:  7.884 ms/op
                 getUser·p0.9999: 13.268 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   2: 3.088 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.729 ms/op
                 getUser·p0.9999: 17.388 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.642 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.949 ms/op
                 getUser·p0.9999: 16.895 ms/op
                 getUser·p1.00:   19.431 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309747
  mean =      3.098 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1296 
    [ 1.250,  2.500) = 21112 
    [ 2.500,  3.750) = 259391 
    [ 3.750,  5.000) = 26700 
    [ 5.000,  6.250) = 636 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 70 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.735 ms/op
     p(99.9900) =     16.944 ms/op
     p(99.9990) =     19.081 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 4.880 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.284 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.109 ±(99.9%) 0.011 ms/op
Iteration   1: 3.980 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.987 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  12.378 ms/op
                 listUser·p0.9999: 15.090 ms/op
                 listUser·p1.00:   15.385 ms/op

Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  16.253 ms/op
                 listUser·p0.9999: 18.257 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 3.973 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.568 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.580 ms/op
                 listUser·p0.9999: 20.050 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240854
  mean =      3.987 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4489 
    [ 2.500,  5.000) = 209735 
    [ 5.000,  7.500) = 25235 
    [ 7.500, 10.000) = 851 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.726 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.437 ms/op
     p(99.9900) =     18.020 ms/op
     p(99.9990) =     21.565 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.431 ± 2.869  ops/ms
ClientGrpc.existUser                       thrpt       3  10.767 ± 0.944  ops/ms
ClientGrpc.getUser                         thrpt       3  10.365 ± 3.507  ops/ms
ClientGrpc.listUser                        thrpt       3   8.073 ± 4.440  ops/ms
ClientGrpc.createUser                       avgt       3   3.057 ± 0.173   ms/op
ClientGrpc.existUser                        avgt       3   2.977 ± 0.348   ms/op
ClientGrpc.getUser                          avgt       3   2.982 ± 0.221   ms/op
ClientGrpc.listUser                         avgt       3   4.053 ± 0.139   ms/op
ClientGrpc.createUser                     sample  308897   3.109 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.572           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.869           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.283           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.166           ms/op
ClientGrpc.existUser                      sample  327494   2.930 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.111           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.310           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.940           ms/op
ClientGrpc.getUser                        sample  309747   3.098 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.642           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.735           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.944           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.431           ms/op
ClientGrpc.listUser                       sample  240854   3.987 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.568           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.726           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.437           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.020           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.889           ms/op
