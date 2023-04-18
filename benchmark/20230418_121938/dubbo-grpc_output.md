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
# Warmup Iteration   1: 4.020 ops/ms
# Warmup Iteration   2: 8.422 ops/ms
# Warmup Iteration   3: 10.065 ops/ms
Iteration   1: 10.323 ops/ms
Iteration   2: 10.290 ops/ms
Iteration   3: 10.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.322 ±(99.9%) 0.563 ops/ms [Average]
  (min, avg, max) = (10.290, 10.322, 10.352), stdev = 0.031
  CI (99.9%): [9.759, 10.884] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 6.971 ops/ms
# Warmup Iteration   2: 10.131 ops/ms
# Warmup Iteration   3: 11.008 ops/ms
Iteration   1: 10.810 ops/ms
Iteration   2: 10.877 ops/ms
Iteration   3: 10.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.671 ±(99.9%) 5.497 ops/ms [Average]
  (min, avg, max) = (10.325, 10.671, 10.877), stdev = 0.301
  CI (99.9%): [5.174, 16.168] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.308 ops/ms
# Warmup Iteration   2: 9.899 ops/ms
# Warmup Iteration   3: 10.204 ops/ms
Iteration   1: 10.229 ops/ms
Iteration   2: 10.239 ops/ms
Iteration   3: 10.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.304 ±(99.9%) 2.199 ops/ms [Average]
  (min, avg, max) = (10.229, 10.304, 10.443), stdev = 0.121
  CI (99.9%): [8.105, 12.502] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.105 ops/ms
# Warmup Iteration   2: 7.614 ops/ms
# Warmup Iteration   3: 7.883 ops/ms
Iteration   1: 8.032 ops/ms
Iteration   2: 8.041 ops/ms
Iteration   3: 8.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.069 ±(99.9%) 1.041 ops/ms [Average]
  (min, avg, max) = (8.032, 8.069, 8.135), stdev = 0.057
  CI (99.9%): [7.028, 9.110] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.596 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.282 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.005 ms/op
Iteration   1: 3.107 ±(99.9%) 0.002 ms/op
Iteration   2: 3.003 ±(99.9%) 0.004 ms/op
Iteration   3: 3.050 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.053 ±(99.9%) 0.952 ms/op [Average]
  (min, avg, max) = (3.003, 3.053, 3.107), stdev = 0.052
  CI (99.9%): [2.102, 4.005] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.841 ±(99.9%) 0.005 ms/op
Iteration   1: 3.006 ±(99.9%) 0.002 ms/op
Iteration   2: 2.959 ±(99.9%) 0.002 ms/op
Iteration   3: 3.021 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.995 ±(99.9%) 0.592 ms/op [Average]
  (min, avg, max) = (2.959, 2.995, 3.021), stdev = 0.032
  CI (99.9%): [2.403, 3.587] (assumes normal distribution)


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
# Warmup Iteration   1: 4.475 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.004 ms/op
Iteration   1: 3.063 ±(99.9%) 0.004 ms/op
Iteration   2: 3.069 ±(99.9%) 0.003 ms/op
Iteration   3: 3.061 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.064 ±(99.9%) 0.080 ms/op [Average]
  (min, avg, max) = (3.061, 3.064, 3.069), stdev = 0.004
  CI (99.9%): [2.984, 3.145] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.248 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.009 ms/op
Iteration   1: 3.951 ±(99.9%) 0.017 ms/op
Iteration   2: 3.900 ±(99.9%) 0.011 ms/op
Iteration   3: 4.010 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.954 ±(99.9%) 1.010 ms/op [Average]
  (min, avg, max) = (3.900, 3.954, 4.010), stdev = 0.055
  CI (99.9%): [2.943, 4.964] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.630 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.121 ms/op
                 createUser·p0.9999: 13.668 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   2: 3.118 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.710 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.602 ms/op
                 createUser·p0.9999: 14.913 ms/op
                 createUser·p1.00:   15.466 ms/op

Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  9.159 ms/op
                 createUser·p0.9999: 19.048 ms/op
                 createUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309522
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18967 
    [ 2.500,  5.000) = 288716 
    [ 5.000,  7.500) = 1402 
    [ 7.500, 10.000) = 209 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      8.364 ms/op
     p(99.9900) =     15.663 ms/op
     p(99.9990) =     20.277 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 4.266 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.005 ms/op
Iteration   1: 2.943 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.933 ms/op
                 existUser·p0.9999: 13.816 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.969 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  6.652 ms/op
                 existUser·p0.9999: 15.421 ms/op
                 existUser·p1.00:   16.663 ms/op

Iteration   3: 3.030 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  9.654 ms/op
                 existUser·p0.9999: 18.121 ms/op
                 existUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322408
  mean =      2.980 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 595 
    [ 1.250,  2.500) = 22963 
    [ 2.500,  3.750) = 289501 
    [ 3.750,  5.000) = 8210 
    [ 5.000,  6.250) = 491 
    [ 6.250,  7.500) = 251 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.727 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      8.736 ms/op
     p(99.9900) =     17.421 ms/op
     p(99.9990) =     18.244 ms/op
     p(99.9999) =     18.317 ms/op
    p(100.0000) =     18.317 ms/op


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.213 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.008 ms/op
Iteration   1: 3.077 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.218 ms/op
                 getUser·p0.9999: 12.891 ms/op
                 getUser·p1.00:   14.680 ms/op

Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.847 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  9.130 ms/op
                 getUser·p0.9999: 14.565 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   3: 3.118 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.882 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  5.979 ms/op
                 getUser·p0.9999: 16.445 ms/op
                 getUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310332
  mean =      3.091 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 459 
    [ 1.250,  2.500) = 15489 
    [ 2.500,  3.750) = 275815 
    [ 3.750,  5.000) = 17259 
    [ 5.000,  6.250) = 685 
    [ 6.250,  7.500) = 275 
    [ 7.500,  8.750) = 103 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 19 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.847 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.766 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     16.739 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 4.839 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.011 ms/op
Iteration   1: 4.072 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.697 ms/op
                 listUser·p0.9999: 21.297 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   2: 3.997 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  14.795 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 4.006 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  16.515 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238377
  mean =      4.025 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2399 
    [ 2.500,  5.000) = 207270 
    [ 5.000,  7.500) = 27114 
    [ 7.500, 10.000) = 1017 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.395 ms/op
     p(99.9900) =     23.014 ms/op
     p(99.9990) =     24.819 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.322 ± 0.563  ops/ms
ClientGrpc.existUser                       thrpt       3  10.671 ± 5.497  ops/ms
ClientGrpc.getUser                         thrpt       3  10.304 ± 2.199  ops/ms
ClientGrpc.listUser                        thrpt       3   8.069 ± 1.041  ops/ms
ClientGrpc.createUser                       avgt       3   3.053 ± 0.952   ms/op
ClientGrpc.existUser                        avgt       3   2.995 ± 0.592   ms/op
ClientGrpc.getUser                          avgt       3   3.064 ± 0.080   ms/op
ClientGrpc.listUser                         avgt       3   3.954 ± 1.010   ms/op
ClientGrpc.createUser                     sample  309522   3.101 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.657           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.875           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.364           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.663           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.447           ms/op
ClientGrpc.existUser                      sample  322408   2.980 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.727           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.428           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.736           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.421           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.317           ms/op
ClientGrpc.getUser                        sample  310332   3.091 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.847           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.766           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.925           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.876           ms/op
ClientGrpc.listUser                       sample  238377   4.025 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.887           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.094           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.395           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.014           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.706           ms/op
