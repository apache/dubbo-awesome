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
# Warmup Iteration   1: 4.364 ops/ms
# Warmup Iteration   2: 9.188 ops/ms
# Warmup Iteration   3: 10.116 ops/ms
Iteration   1: 10.840 ops/ms
Iteration   2: 10.778 ops/ms
Iteration   3: 10.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.823 ±(99.9%) 0.719 ops/ms [Average]
  (min, avg, max) = (10.778, 10.823, 10.851), stdev = 0.039
  CI (99.9%): [10.104, 11.542] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.536 ops/ms
# Warmup Iteration   2: 10.939 ops/ms
# Warmup Iteration   3: 10.935 ops/ms
Iteration   1: 11.143 ops/ms
Iteration   2: 11.181 ops/ms
Iteration   3: 11.156 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.160 ±(99.9%) 0.352 ops/ms [Average]
  (min, avg, max) = (11.143, 11.160, 11.181), stdev = 0.019
  CI (99.9%): [10.808, 11.512] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.538 ops/ms
# Warmup Iteration   2: 10.324 ops/ms
# Warmup Iteration   3: 10.394 ops/ms
Iteration   1: 10.716 ops/ms
Iteration   2: 10.775 ops/ms
Iteration   3: 10.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.731 ±(99.9%) 0.712 ops/ms [Average]
  (min, avg, max) = (10.702, 10.731, 10.775), stdev = 0.039
  CI (99.9%): [10.019, 11.443] (assumes normal distribution)


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
# Warmup Iteration   1: 5.862 ops/ms
# Warmup Iteration   2: 7.848 ops/ms
# Warmup Iteration   3: 8.031 ops/ms
Iteration   1: 7.889 ops/ms
Iteration   2: 7.976 ops/ms
Iteration   3: 8.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.008 ±(99.9%) 2.514 ops/ms [Average]
  (min, avg, max) = (7.889, 8.008, 8.159), stdev = 0.138
  CI (99.9%): [5.495, 10.522] (assumes normal distribution)


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
# Warmup Iteration   1: 4.279 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.003 ms/op
Iteration   1: 2.995 ±(99.9%) 0.007 ms/op
Iteration   2: 3.026 ±(99.9%) 0.002 ms/op
Iteration   3: 2.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.991 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (2.952, 2.991, 3.026), stdev = 0.037
  CI (99.9%): [2.310, 3.672] (assumes normal distribution)


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.983 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.002 ms/op
Iteration   1: 2.866 ±(99.9%) 0.002 ms/op
Iteration   2: 2.842 ±(99.9%) 0.002 ms/op
Iteration   3: 2.849 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.852 ±(99.9%) 0.222 ms/op [Average]
  (min, avg, max) = (2.842, 2.852, 2.866), stdev = 0.012
  CI (99.9%): [2.630, 3.074] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.003 ms/op
Iteration   1: 2.984 ±(99.9%) 0.003 ms/op
Iteration   2: 2.942 ±(99.9%) 0.003 ms/op
Iteration   3: 2.974 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.967 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (2.942, 2.967, 2.984), stdev = 0.022
  CI (99.9%): [2.569, 3.364] (assumes normal distribution)


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
# Warmup Iteration   1: 5.135 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.958 ±(99.9%) 0.012 ms/op
Iteration   1: 3.891 ±(99.9%) 0.020 ms/op
Iteration   2: 3.944 ±(99.9%) 0.020 ms/op
Iteration   3: 3.870 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.902 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (3.870, 3.902, 3.944), stdev = 0.038
  CI (99.9%): [3.203, 4.601] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.006 ms/op
Iteration   1: 2.988 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.831 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  7.920 ms/op
                 createUser·p0.9999: 13.386 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 3.002 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  7.085 ms/op
                 createUser·p0.9999: 15.937 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   3: 3.070 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  14.121 ms/op
                 createUser·p0.9999: 16.210 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317665
  mean =      3.020 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 521 
    [ 1.250,  2.500) = 21948 
    [ 2.500,  3.750) = 279513 
    [ 3.750,  5.000) = 14294 
    [ 5.000,  6.250) = 561 
    [ 6.250,  7.500) = 306 
    [ 7.500,  8.750) = 118 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 125 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =     12.310 ms/op
     p(99.9900) =     15.913 ms/op
     p(99.9990) =     16.766 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.860 ±(99.9%) 0.004 ms/op
Iteration   1: 2.869 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.660 ms/op
                 existUser·p0.9999: 12.354 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   2: 2.864 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  6.082 ms/op
                 existUser·p0.9999: 13.737 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.173 ms/op
                 existUser·p0.999:  6.764 ms/op
                 existUser·p0.9999: 15.827 ms/op
                 existUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333767
  mean =      2.874 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1006 
    [ 1.250,  2.500) = 44437 
    [ 2.500,  3.750) = 280515 
    [ 3.750,  5.000) = 6703 
    [ 5.000,  6.250) = 652 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      6.578 ms/op
     p(99.9900) =     15.254 ms/op
     p(99.9990) =     16.204 ms/op
     p(99.9999) =     16.286 ms/op
    p(100.0000) =     16.286 ms/op


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.006 ms/op
Iteration   1: 3.022 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.700 ms/op
                 getUser·p0.9999: 12.793 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   2: 3.004 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  6.734 ms/op
                 getUser·p0.9999: 20.677 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.625 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  6.695 ms/op
                 getUser·p0.9999: 15.900 ms/op
                 getUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320122
  mean =      2.998 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25010 
    [ 2.500,  5.000) = 293822 
    [ 5.000,  7.500) = 1031 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      6.971 ms/op
     p(99.9900) =     20.071 ms/op
     p(99.9990) =     21.515 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 5.585 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.011 ms/op
Iteration   1: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.255 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 19.226 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 3.933 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.519 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  15.277 ms/op
                 listUser·p0.9999: 22.507 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   3: 3.972 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.657 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  16.285 ms/op
                 listUser·p0.9999: 26.399 ms/op
                 listUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243084
  mean =      3.947 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3082 
    [ 2.500,  5.000) = 215681 
    [ 5.000,  7.500) = 22805 
    [ 7.500, 10.000) = 1028 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.519 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.021 ms/op
     p(99.9000) =     15.088 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     28.129 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.823 ± 0.719  ops/ms
ClientGrpc.existUser                       thrpt       3  11.160 ± 0.352  ops/ms
ClientGrpc.getUser                         thrpt       3  10.731 ± 0.712  ops/ms
ClientGrpc.listUser                        thrpt       3   8.008 ± 2.514  ops/ms
ClientGrpc.createUser                       avgt       3   2.991 ± 0.681   ms/op
ClientGrpc.existUser                        avgt       3   2.852 ± 0.222   ms/op
ClientGrpc.getUser                          avgt       3   2.967 ± 0.398   ms/op
ClientGrpc.listUser                         avgt       3   3.902 ± 0.699   ms/op
ClientGrpc.createUser                     sample  317665   3.020 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.800           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.518           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.310           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.913           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.039           ms/op
ClientGrpc.existUser                      sample  333767   2.874 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.526           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.578           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.254           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.286           ms/op
ClientGrpc.getUser                        sample  320122   2.998 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.566           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.971           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.071           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.660           ms/op
ClientGrpc.listUser                       sample  243084   3.947 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.519           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.088           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.347           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.246           ms/op
