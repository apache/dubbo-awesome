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
# Warmup Iteration   1: 4.925 ops/ms
# Warmup Iteration   2: 9.552 ops/ms
# Warmup Iteration   3: 9.919 ops/ms
Iteration   1: 10.858 ops/ms
Iteration   2: 10.715 ops/ms
Iteration   3: 10.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.734 ±(99.9%) 2.090 ops/ms [Average]
  (min, avg, max) = (10.631, 10.734, 10.858), stdev = 0.115
  CI (99.9%): [8.645, 12.824] (assumes normal distribution)


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
# Warmup Iteration   1: 8.281 ops/ms
# Warmup Iteration   2: 10.930 ops/ms
# Warmup Iteration   3: 11.070 ops/ms
Iteration   1: 11.571 ops/ms
Iteration   2: 11.231 ops/ms
Iteration   3: 11.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.295 ±(99.9%) 4.566 ops/ms [Average]
  (min, avg, max) = (11.083, 11.295, 11.571), stdev = 0.250
  CI (99.9%): [6.729, 15.862] (assumes normal distribution)


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
# Warmup Iteration   1: 7.215 ops/ms
# Warmup Iteration   2: 10.247 ops/ms
# Warmup Iteration   3: 10.542 ops/ms
Iteration   1: 10.535 ops/ms
Iteration   2: 10.634 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.613 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (10.535, 10.613, 10.669), stdev = 0.070
  CI (99.9%): [9.340, 11.886] (assumes normal distribution)


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
# Warmup Iteration   1: 5.501 ops/ms
# Warmup Iteration   2: 8.102 ops/ms
# Warmup Iteration   3: 8.286 ops/ms
Iteration   1: 8.259 ops/ms
Iteration   2: 8.343 ops/ms
Iteration   3: 8.288 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.297 ±(99.9%) 0.779 ops/ms [Average]
  (min, avg, max) = (8.259, 8.297, 8.343), stdev = 0.043
  CI (99.9%): [7.518, 9.076] (assumes normal distribution)


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
# Warmup Iteration   1: 4.205 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.010 ms/op
Iteration   1: 2.969 ±(99.9%) 0.002 ms/op
Iteration   2: 2.966 ±(99.9%) 0.002 ms/op
Iteration   3: 3.000 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.978 ±(99.9%) 0.346 ms/op [Average]
  (min, avg, max) = (2.966, 2.978, 3.000), stdev = 0.019
  CI (99.9%): [2.632, 3.324] (assumes normal distribution)


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
# Warmup Iteration   1: 3.688 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.915 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.004 ms/op
Iteration   1: 2.852 ±(99.9%) 0.003 ms/op
Iteration   2: 2.849 ±(99.9%) 0.003 ms/op
Iteration   3: 2.808 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.836 ±(99.9%) 0.449 ms/op [Average]
  (min, avg, max) = (2.808, 2.836, 2.852), stdev = 0.025
  CI (99.9%): [2.387, 3.285] (assumes normal distribution)


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
# Warmup Iteration   1: 3.918 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.003 ms/op
Iteration   2: 2.980 ±(99.9%) 0.002 ms/op
Iteration   3: 2.962 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.962 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (2.943, 2.962, 2.980), stdev = 0.018
  CI (99.9%): [2.629, 3.294] (assumes normal distribution)


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
# Warmup Iteration   1: 5.169 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.840 ±(99.9%) 0.038 ms/op
Iteration   1: 3.879 ±(99.9%) 0.019 ms/op
Iteration   2: 3.843 ±(99.9%) 0.018 ms/op
Iteration   3: 3.931 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.884 ±(99.9%) 0.808 ms/op [Average]
  (min, avg, max) = (3.843, 3.884, 3.931), stdev = 0.044
  CI (99.9%): [3.077, 4.692] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  11.386 ms/op
                 createUser·p0.9999: 15.352 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.361 ms/op
                 createUser·p0.9999: 17.068 ms/op
                 createUser·p1.00:   17.302 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  6.739 ms/op
                 createUser·p0.9999: 18.553 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319408
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1767 
    [ 1.250,  2.500) = 24042 
    [ 2.500,  3.750) = 278319 
    [ 3.750,  5.000) = 13926 
    [ 5.000,  6.250) = 756 
    [ 6.250,  7.500) = 218 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 72 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.987 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     18.934 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 3.555 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
Iteration   1: 2.888 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.744 ms/op
                 existUser·p0.9999: 16.102 ms/op
                 existUser·p1.00:   16.450 ms/op

Iteration   2: 2.880 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.536 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  6.801 ms/op
                 existUser·p0.9999: 13.119 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.602 ms/op
                 existUser·p0.9999: 14.778 ms/op
                 existUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332393
  mean =      2.888 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2117 
    [ 1.250,  2.500) = 41740 
    [ 2.500,  3.750) = 277993 
    [ 3.750,  5.000) = 9305 
    [ 5.000,  6.250) = 739 
    [ 6.250,  7.500) = 198 
    [ 7.500,  8.750) = 123 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.088 ms/op
     p(99.9900) =     15.123 ms/op
     p(99.9990) =     16.384 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.555 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  9.907 ms/op
                 getUser·p0.9999: 12.938 ms/op
                 getUser·p1.00:   13.304 ms/op

Iteration   2: 2.996 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.659 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.547 ms/op
                 getUser·p0.999:  7.164 ms/op
                 getUser·p0.9999: 14.625 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.724 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320676
  mean =      2.993 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1844 
    [ 1.250,  2.500) = 29341 
    [ 2.500,  3.750) = 272122 
    [ 3.750,  5.000) = 15755 
    [ 5.000,  6.250) = 879 
    [ 6.250,  7.500) = 377 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 83 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.754 ms/op
     p(99.9900) =     14.776 ms/op
     p(99.9990) =     17.157 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.011 ms/op
Iteration   1: 3.836 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  12.773 ms/op
                 listUser·p0.9999: 15.150 ms/op
                 listUser·p1.00:   16.089 ms/op

Iteration   2: 3.859 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  17.866 ms/op
                 listUser·p0.9999: 25.072 ms/op
                 listUser·p1.00:   25.625 ms/op

Iteration   3: 3.834 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 18.961 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249721
  mean =      3.843 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5639 
    [ 2.500,  5.000) = 224493 
    [ 5.000,  7.500) = 18372 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     14.920 ms/op
     p(99.9900) =     23.560 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.734 ± 2.090  ops/ms
ClientGrpc.existUser                       thrpt       3  11.295 ± 4.566  ops/ms
ClientGrpc.getUser                         thrpt       3  10.613 ± 1.273  ops/ms
ClientGrpc.listUser                        thrpt       3   8.297 ± 0.779  ops/ms
ClientGrpc.createUser                       avgt       3   2.978 ± 0.346   ms/op
ClientGrpc.existUser                        avgt       3   2.836 ± 0.449   ms/op
ClientGrpc.getUser                          avgt       3   2.962 ± 0.332   ms/op
ClientGrpc.listUser                         avgt       3   3.884 ± 0.808   ms/op
ClientGrpc.createUser                     sample  319408   3.006 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.636           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.987           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.367           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.038           ms/op
ClientGrpc.existUser                      sample  332393   2.888 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.536           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.088           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.123           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.450           ms/op
ClientGrpc.getUser                        sample  320676   2.993 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.555           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.754           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.776           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.302           ms/op
ClientGrpc.listUser                       sample  249721   3.843 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.866           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.703           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.920           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.560           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
