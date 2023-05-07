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
# Warmup Iteration   1: 4.721 ops/ms
# Warmup Iteration   2: 9.194 ops/ms
# Warmup Iteration   3: 10.856 ops/ms
Iteration   1: 10.709 ops/ms
Iteration   2: 10.545 ops/ms
Iteration   3: 10.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.691 ±(99.9%) 2.526 ops/ms [Average]
  (min, avg, max) = (10.545, 10.691, 10.820), stdev = 0.138
  CI (99.9%): [8.165, 13.217] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.912 ops/ms
# Warmup Iteration   2: 11.051 ops/ms
# Warmup Iteration   3: 11.258 ops/ms
Iteration   1: 11.395 ops/ms
Iteration   2: 11.142 ops/ms
Iteration   3: 11.513 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.350 ±(99.9%) 3.466 ops/ms [Average]
  (min, avg, max) = (11.142, 11.350, 11.513), stdev = 0.190
  CI (99.9%): [7.885, 14.816] (assumes normal distribution)


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
# Warmup Iteration   1: 7.784 ops/ms
# Warmup Iteration   2: 10.505 ops/ms
# Warmup Iteration   3: 10.777 ops/ms
Iteration   1: 10.843 ops/ms
Iteration   2: 10.780 ops/ms
Iteration   3: 11.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.874 ±(99.9%) 2.061 ops/ms [Average]
  (min, avg, max) = (10.780, 10.874, 11.000), stdev = 0.113
  CI (99.9%): [8.814, 12.935] (assumes normal distribution)


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
# Warmup Iteration   1: 5.737 ops/ms
# Warmup Iteration   2: 8.109 ops/ms
# Warmup Iteration   3: 8.215 ops/ms
Iteration   1: 8.163 ops/ms
Iteration   2: 8.329 ops/ms
Iteration   3: 8.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.215 ±(99.9%) 1.805 ops/ms [Average]
  (min, avg, max) = (8.153, 8.215, 8.329), stdev = 0.099
  CI (99.9%): [6.410, 10.020] (assumes normal distribution)


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
# Warmup Iteration   1: 3.999 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.003 ms/op
Iteration   1: 2.919 ±(99.9%) 0.007 ms/op
Iteration   2: 2.964 ±(99.9%) 0.003 ms/op
Iteration   3: 2.948 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.944 ±(99.9%) 0.412 ms/op [Average]
  (min, avg, max) = (2.919, 2.944, 2.964), stdev = 0.023
  CI (99.9%): [2.532, 3.356] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.623 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.920 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.004 ms/op
Iteration   1: 2.845 ±(99.9%) 0.003 ms/op
Iteration   2: 2.782 ±(99.9%) 0.004 ms/op
Iteration   3: 2.706 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.778 ±(99.9%) 1.273 ms/op [Average]
  (min, avg, max) = (2.706, 2.778, 2.845), stdev = 0.070
  CI (99.9%): [1.505, 4.050] (assumes normal distribution)


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
# Warmup Iteration   1: 3.907 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.004 ms/op
Iteration   1: 2.930 ±(99.9%) 0.003 ms/op
Iteration   2: 2.909 ±(99.9%) 0.004 ms/op
Iteration   3: 2.992 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.944 ±(99.9%) 0.779 ms/op [Average]
  (min, avg, max) = (2.909, 2.944, 2.992), stdev = 0.043
  CI (99.9%): [2.165, 3.723] (assumes normal distribution)


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
# Warmup Iteration   1: 5.004 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.861 ±(99.9%) 0.009 ms/op
Iteration   1: 3.849 ±(99.9%) 0.010 ms/op
Iteration   2: 3.891 ±(99.9%) 0.012 ms/op
Iteration   3: 3.838 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.859 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.838, 3.859, 3.891), stdev = 0.028
  CI (99.9%): [3.346, 4.373] (assumes normal distribution)


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
# Warmup Iteration   1: 4.110 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.092 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.926 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.346 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  11.125 ms/op
                 createUser·p0.9999: 23.464 ms/op
                 createUser·p1.00:   23.855 ms/op

Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.733 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  6.914 ms/op
                 createUser·p0.9999: 15.799 ms/op
                 createUser·p1.00:   16.482 ms/op

Iteration   3: 2.953 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.608 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.564 ms/op
                 createUser·p0.9999: 29.721 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326059
  mean =      2.943 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36903 
    [ 2.500,  5.000) = 287765 
    [ 5.000,  7.500) = 960 
    [ 7.500, 10.000) = 144 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.608 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.747 ms/op
     p(99.9900) =     25.262 ms/op
     p(99.9990) =     29.876 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 3.803 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.901 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.796 ±(99.9%) 0.006 ms/op
Iteration   1: 2.857 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  6.991 ms/op
                 existUser·p0.9999: 11.253 ms/op
                 existUser·p1.00:   11.518 ms/op

Iteration   2: 2.901 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.504 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.832 ms/op
                 existUser·p0.9999: 13.844 ms/op
                 existUser·p1.00:   14.369 ms/op

Iteration   3: 2.819 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  6.955 ms/op
                 existUser·p0.9999: 27.317 ms/op
                 existUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335600
  mean =      2.858 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57966 
    [ 2.500,  5.000) = 276184 
    [ 5.000,  7.500) = 1193 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      6.930 ms/op
     p(99.9900) =     14.533 ms/op
     p(99.9990) =     27.513 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.657 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  9.631 ms/op
                 getUser·p0.9999: 12.033 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   2: 2.948 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.685 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.384 ms/op
                 getUser·p0.9999: 13.107 ms/op
                 getUser·p1.00:   13.435 ms/op

Iteration   3: 2.965 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.963 ms/op
                 getUser·p0.9999: 13.831 ms/op
                 getUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322238
  mean =      2.980 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1414 
    [ 1.250,  2.500) = 25338 
    [ 2.500,  3.750) = 283705 
    [ 3.750,  5.000) = 10768 
    [ 5.000,  6.250) = 476 
    [ 6.250,  7.500) = 209 
    [ 7.500,  8.750) = 86 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 95 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.537 ms/op
     p(99.9900) =     13.530 ms/op
     p(99.9990) =     14.005 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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
# Warmup Iteration   1: 4.137 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.090 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.921 ±(99.9%) 0.010 ms/op
Iteration   1: 3.877 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  12.862 ms/op
                 listUser·p0.9999: 18.907 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 3.982 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.710 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.947 ms/op
                 listUser·p0.999:  26.827 ms/op
                 listUser·p0.9999: 33.412 ms/op
                 listUser·p1.00:   35.717 ms/op

Iteration   3: 4.517 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.905 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   25.747 ms/op
                 listUser·p0.999:  37.028 ms/op
                 listUser·p0.9999: 44.804 ms/op
                 listUser·p1.00:   46.465 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233782
  mean =      4.107 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 208644 
    [ 5.000, 10.000) = 22329 
    [10.000, 15.000) = 542 
    [15.000, 20.000) = 640 
    [20.000, 25.000) = 656 
    [25.000, 30.000) = 637 
    [30.000, 35.000) = 231 
    [35.000, 40.000) = 61 
    [40.000, 45.000) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =     14.320 ms/op
     p(99.9000) =     31.661 ms/op
     p(99.9900) =     42.090 ms/op
     p(99.9990) =     46.044 ms/op
     p(99.9999) =     46.465 ms/op
    p(100.0000) =     46.465 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.691 ± 2.526  ops/ms
ClientGrpc.existUser                       thrpt       3  11.350 ± 3.466  ops/ms
ClientGrpc.getUser                         thrpt       3  10.874 ± 2.061  ops/ms
ClientGrpc.listUser                        thrpt       3   8.215 ± 1.805  ops/ms
ClientGrpc.createUser                       avgt       3   2.944 ± 0.412   ms/op
ClientGrpc.existUser                        avgt       3   2.778 ± 1.273   ms/op
ClientGrpc.getUser                          avgt       3   2.944 ± 0.779   ms/op
ClientGrpc.listUser                         avgt       3   3.859 ± 0.514   ms/op
ClientGrpc.createUser                     sample  326059   2.943 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.608           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.747           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.262           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.950           ms/op
ClientGrpc.existUser                      sample  335600   2.858 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.504           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.847           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.930           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.533           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.591           ms/op
ClientGrpc.getUser                        sample  322238   2.980 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.657           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.537           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.530           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.991           ms/op
ClientGrpc.listUser                       sample  233782   4.107 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.710           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.947           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          14.320           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          31.661           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          42.090           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          46.465           ms/op
