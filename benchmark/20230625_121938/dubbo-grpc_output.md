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
# Warmup Iteration   1: 4.391 ops/ms
# Warmup Iteration   2: 9.132 ops/ms
# Warmup Iteration   3: 10.319 ops/ms
Iteration   1: 10.744 ops/ms
Iteration   2: 10.689 ops/ms
Iteration   3: 10.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.749 ±(99.9%) 1.141 ops/ms [Average]
  (min, avg, max) = (10.689, 10.749, 10.814), stdev = 0.063
  CI (99.9%): [9.609, 11.890] (assumes normal distribution)


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
# Warmup Iteration   1: 8.345 ops/ms
# Warmup Iteration   2: 11.051 ops/ms
# Warmup Iteration   3: 11.109 ops/ms
Iteration   1: 11.205 ops/ms
Iteration   2: 11.277 ops/ms
Iteration   3: 11.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.192 ±(99.9%) 1.669 ops/ms [Average]
  (min, avg, max) = (11.095, 11.192, 11.277), stdev = 0.091
  CI (99.9%): [9.523, 12.861] (assumes normal distribution)


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
# Warmup Iteration   1: 7.795 ops/ms
# Warmup Iteration   2: 10.458 ops/ms
# Warmup Iteration   3: 10.744 ops/ms
Iteration   1: 10.824 ops/ms
Iteration   2: 10.759 ops/ms
Iteration   3: 10.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.748 ±(99.9%) 1.511 ops/ms [Average]
  (min, avg, max) = (10.660, 10.748, 10.824), stdev = 0.083
  CI (99.9%): [9.237, 12.259] (assumes normal distribution)


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
# Warmup Iteration   1: 5.832 ops/ms
# Warmup Iteration   2: 8.224 ops/ms
# Warmup Iteration   3: 8.298 ops/ms
Iteration   1: 8.251 ops/ms
Iteration   2: 8.350 ops/ms
Iteration   3: 8.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.285 ±(99.9%) 1.021 ops/ms [Average]
  (min, avg, max) = (8.251, 8.285, 8.350), stdev = 0.056
  CI (99.9%): [7.265, 9.306] (assumes normal distribution)


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.002 ms/op
Iteration   1: 3.017 ±(99.9%) 0.005 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 2.951 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.991 ±(99.9%) 0.647 ms/op [Average]
  (min, avg, max) = (2.951, 2.991, 3.017), stdev = 0.035
  CI (99.9%): [2.344, 3.638] (assumes normal distribution)


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.857 ±(99.9%) 0.004 ms/op
Iteration   1: 2.842 ±(99.9%) 0.004 ms/op
Iteration   2: 2.886 ±(99.9%) 0.002 ms/op
Iteration   3: 2.836 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.854 ±(99.9%) 0.499 ms/op [Average]
  (min, avg, max) = (2.836, 2.854, 2.886), stdev = 0.027
  CI (99.9%): [2.356, 3.353] (assumes normal distribution)


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
# Warmup Iteration   1: 3.903 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.006 ms/op
Iteration   2: 2.961 ±(99.9%) 0.002 ms/op
Iteration   3: 2.927 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.957 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (2.927, 2.957, 2.984), stdev = 0.028
  CI (99.9%): [2.438, 3.477] (assumes normal distribution)


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
# Warmup Iteration   1: 5.279 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.011 ms/op
Iteration   1: 3.813 ±(99.9%) 0.008 ms/op
Iteration   2: 3.800 ±(99.9%) 0.026 ms/op
Iteration   3: 3.768 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.793 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (3.768, 3.793, 3.813), stdev = 0.023
  CI (99.9%): [3.377, 4.210] (assumes normal distribution)


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
# Warmup Iteration   1: 4.056 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.007 ms/op
Iteration   1: 2.984 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.713 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.310 ms/op
                 createUser·p0.9999: 12.129 ms/op
                 createUser·p1.00:   12.468 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.981 ms/op
                 createUser·p0.9999: 16.328 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   3: 2.951 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.270 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.408 ms/op
                 createUser·p0.95:   3.703 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  9.809 ms/op
                 createUser·p0.9999: 24.478 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322722
  mean =      2.976 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32297 
    [ 2.500,  5.000) = 289277 
    [ 5.000,  7.500) = 776 
    [ 7.500, 10.000) = 112 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.270 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      8.152 ms/op
     p(99.9900) =     20.970 ms/op
     p(99.9990) =     24.765 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 3.862 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.956 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.888 ±(99.9%) 0.005 ms/op
Iteration   1: 2.841 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.737 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.334 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.619 ms/op
                 existUser·p0.9999: 11.415 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 2.884 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.497 ms/op
                 existUser·p0.9999: 20.838 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.634 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.363 ms/op
                 existUser·p0.9999: 21.233 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333768
  mean =      2.875 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45057 
    [ 2.500,  5.000) = 287810 
    [ 5.000,  7.500) = 633 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      6.906 ms/op
     p(99.9900) =     20.992 ms/op
     p(99.9990) =     21.539 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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
# Warmup Iteration   1: 4.014 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.426 ms/op
                 getUser·p0.9999: 14.543 ms/op
                 getUser·p1.00:   15.417 ms/op

Iteration   2: 2.993 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.651 ms/op
                 getUser·p0.9999: 15.428 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   3: 2.966 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.563 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.947 ms/op
                 getUser·p0.9999: 32.014 ms/op
                 getUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321566
  mean =      2.984 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33934 
    [ 2.500,  5.000) = 286372 
    [ 5.000,  7.500) = 915 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.563 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.778 ms/op
     p(99.9900) =     28.957 ms/op
     p(99.9990) =     33.260 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 5.273 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.879 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.901 ±(99.9%) 0.011 ms/op
Iteration   1: 3.891 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.743 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  12.154 ms/op
                 listUser·p0.9999: 13.956 ms/op
                 listUser·p1.00:   14.303 ms/op

Iteration   2: 3.917 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  14.921 ms/op
                 listUser·p0.9999: 27.547 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   3: 3.886 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  14.299 ms/op
                 listUser·p0.9999: 22.792 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246124
  mean =      3.898 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5317 
    [ 2.500,  5.000) = 219748 
    [ 5.000,  7.500) = 19792 
    [ 7.500, 10.000) = 687 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.495 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     13.611 ms/op
     p(99.9900) =     25.670 ms/op
     p(99.9990) =     27.689 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.749 ± 1.141  ops/ms
ClientGrpc.existUser                       thrpt       3  11.192 ± 1.669  ops/ms
ClientGrpc.getUser                         thrpt       3  10.748 ± 1.511  ops/ms
ClientGrpc.listUser                        thrpt       3   8.285 ± 1.021  ops/ms
ClientGrpc.createUser                       avgt       3   2.991 ± 0.647   ms/op
ClientGrpc.existUser                        avgt       3   2.854 ± 0.499   ms/op
ClientGrpc.getUser                          avgt       3   2.957 ± 0.520   ms/op
ClientGrpc.listUser                         avgt       3   3.793 ± 0.416   ms/op
ClientGrpc.createUser                     sample  322722   2.976 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.270           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.497           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.152           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.970           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.904           ms/op
ClientGrpc.existUser                      sample  333768   2.875 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.634           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.906           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.992           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  321566   2.984 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.563           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.764           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.778           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          28.957           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.489           ms/op
ClientGrpc.listUser                       sample  246124   3.898 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.743           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.495           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.611           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.670           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.722           ms/op
