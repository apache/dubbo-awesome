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
# Warmup Iteration   1: 4.882 ops/ms
# Warmup Iteration   2: 8.609 ops/ms
# Warmup Iteration   3: 10.144 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.784 ops/ms
Iteration   3: 10.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.755 ±(99.9%) 2.580 ops/ms [Average]
  (min, avg, max) = (10.602, 10.755, 10.880), stdev = 0.141
  CI (99.9%): [8.175, 13.336] (assumes normal distribution)


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
# Warmup Iteration   1: 8.074 ops/ms
# Warmup Iteration   2: 10.898 ops/ms
# Warmup Iteration   3: 11.300 ops/ms
Iteration   1: 11.407 ops/ms
Iteration   2: 11.528 ops/ms
Iteration   3: 11.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.566 ±(99.9%) 3.298 ops/ms [Average]
  (min, avg, max) = (11.407, 11.566, 11.763), stdev = 0.181
  CI (99.9%): [8.268, 14.864] (assumes normal distribution)


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
# Warmup Iteration   1: 8.261 ops/ms
# Warmup Iteration   2: 10.353 ops/ms
# Warmup Iteration   3: 10.824 ops/ms
Iteration   1: 10.860 ops/ms
Iteration   2: 10.726 ops/ms
Iteration   3: 10.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.806 ±(99.9%) 1.293 ops/ms [Average]
  (min, avg, max) = (10.726, 10.806, 10.860), stdev = 0.071
  CI (99.9%): [9.514, 12.099] (assumes normal distribution)


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
# Warmup Iteration   1: 6.731 ops/ms
# Warmup Iteration   2: 7.973 ops/ms
# Warmup Iteration   3: 8.291 ops/ms
Iteration   1: 8.352 ops/ms
Iteration   2: 8.266 ops/ms
Iteration   3: 8.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.300 ±(99.9%) 0.842 ops/ms [Average]
  (min, avg, max) = (8.266, 8.300, 8.352), stdev = 0.046
  CI (99.9%): [7.458, 9.142] (assumes normal distribution)


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
# Warmup Iteration   1: 4.001 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 2.963 ±(99.9%) 0.003 ms/op
Iteration   1: 2.969 ±(99.9%) 0.003 ms/op
Iteration   2: 2.961 ±(99.9%) 0.002 ms/op
Iteration   3: 2.984 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.971 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (2.961, 2.971, 2.984), stdev = 0.011
  CI (99.9%): [2.765, 3.178] (assumes normal distribution)


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
# Warmup Iteration   1: 3.086 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.917 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.817 ±(99.9%) 0.006 ms/op
Iteration   1: 2.851 ±(99.9%) 0.003 ms/op
Iteration   2: 2.812 ±(99.9%) 0.003 ms/op
Iteration   3: 2.811 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.824 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (2.811, 2.824, 2.851), stdev = 0.023
  CI (99.9%): [2.413, 3.236] (assumes normal distribution)


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
# Warmup Iteration   1: 3.551 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.002 ms/op
Iteration   1: 2.935 ±(99.9%) 0.004 ms/op
Iteration   2: 2.915 ±(99.9%) 0.002 ms/op
Iteration   3: 2.922 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.924 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (2.915, 2.924, 2.935), stdev = 0.011
  CI (99.9%): [2.732, 3.116] (assumes normal distribution)


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
# Warmup Iteration   1: 4.099 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.010 ms/op
Iteration   1: 3.888 ±(99.9%) 0.034 ms/op
Iteration   2: 3.791 ±(99.9%) 0.010 ms/op
Iteration   3: 3.800 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.826 ±(99.9%) 0.979 ms/op [Average]
  (min, avg, max) = (3.791, 3.826, 3.888), stdev = 0.054
  CI (99.9%): [2.848, 4.805] (assumes normal distribution)


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
# Warmup Iteration   1: 3.906 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.006 ms/op
Iteration   1: 2.942 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.707 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.513 ms/op
                 createUser·p0.9999: 16.978 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 2.968 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 19.176 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.532 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  9.831 ms/op
                 createUser·p0.9999: 14.634 ms/op
                 createUser·p1.00:   14.860 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324491
  mean =      2.959 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37413 
    [ 2.500,  5.000) = 285520 
    [ 5.000,  7.500) = 1127 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.782 ms/op
     p(99.9900) =     17.984 ms/op
     p(99.9990) =     19.579 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 3.651 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.837 ±(99.9%) 0.006 ms/op
Iteration   1: 2.845 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   2.826 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  5.800 ms/op
                 existUser·p0.9999: 13.791 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   2: 2.826 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   2.814 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  6.521 ms/op
                 existUser·p0.9999: 15.599 ms/op
                 existUser·p1.00:   16.630 ms/op

Iteration   3: 2.860 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.111 ms/op
                 existUser·p0.9999: 14.461 ms/op
                 existUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 337370
  mean =      2.844 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2737 
    [ 1.250,  2.500) = 54585 
    [ 2.500,  3.750) = 269408 
    [ 3.750,  5.000) = 9591 
    [ 5.000,  6.250) = 743 
    [ 6.250,  7.500) = 142 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      6.128 ms/op
     p(99.9900) =     14.890 ms/op
     p(99.9990) =     15.739 ms/op
     p(99.9999) =     16.630 ms/op
    p(100.0000) =     16.630 ms/op


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
# Warmup Iteration   1: 4.073 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  7.496 ms/op
                 getUser·p0.9999: 25.207 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.697 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.997 ms/op
                 getUser·p0.9999: 15.797 ms/op
                 getUser·p1.00:   16.171 ms/op

Iteration   3: 2.929 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.463 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.438 ms/op
                 getUser·p0.9999: 21.018 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326053
  mean =      2.945 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39672 
    [ 2.500,  5.000) = 284955 
    [ 5.000,  7.500) = 1050 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.463 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =      8.003 ms/op
     p(99.9900) =     22.719 ms/op
     p(99.9990) =     25.362 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 5.193 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.011 ms/op
Iteration   1: 3.899 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.835 ms/op
                 listUser·p0.999:  15.693 ms/op
                 listUser·p0.9999: 23.015 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 3.760 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.293 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  12.999 ms/op
                 listUser·p0.9999: 15.081 ms/op
                 listUser·p1.00:   15.991 ms/op

Iteration   3: 3.817 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.746 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  15.732 ms/op
                 listUser·p0.9999: 18.678 ms/op
                 listUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251178
  mean =      3.824 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4147 
    [ 2.500,  5.000) = 228736 
    [ 5.000,  7.500) = 17161 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.636 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     23.732 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.755 ± 2.580  ops/ms
ClientGrpc.existUser                       thrpt       3  11.566 ± 3.298  ops/ms
ClientGrpc.getUser                         thrpt       3  10.806 ± 1.293  ops/ms
ClientGrpc.listUser                        thrpt       3   8.300 ± 0.842  ops/ms
ClientGrpc.createUser                       avgt       3   2.971 ± 0.207   ms/op
ClientGrpc.existUser                        avgt       3   2.824 ± 0.411   ms/op
ClientGrpc.getUser                          avgt       3   2.924 ± 0.192   ms/op
ClientGrpc.listUser                         avgt       3   3.826 ± 0.979   ms/op
ClientGrpc.createUser                     sample  324491   2.959 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.532           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.941           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.782           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.984           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.742           ms/op
ClientGrpc.existUser                      sample  337370   2.844 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.499           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.830           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.128           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.890           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.630           ms/op
ClientGrpc.getUser                        sample  326053   2.945 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.463           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.929           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.481           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.003           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.719           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.494           ms/op
ClientGrpc.listUser                       sample  251178   3.824 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.293           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.743           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.636           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.463           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.347           ms/op
