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
# Warmup Iteration   1: 4.537 ops/ms
# Warmup Iteration   2: 9.486 ops/ms
# Warmup Iteration   3: 10.364 ops/ms
Iteration   1: 10.644 ops/ms
Iteration   2: 10.695 ops/ms
Iteration   3: 10.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.718 ±(99.9%) 1.597 ops/ms [Average]
  (min, avg, max) = (10.644, 10.718, 10.815), stdev = 0.088
  CI (99.9%): [9.121, 12.315] (assumes normal distribution)


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
# Warmup Iteration   1: 7.859 ops/ms
# Warmup Iteration   2: 10.750 ops/ms
# Warmup Iteration   3: 11.403 ops/ms
Iteration   1: 11.293 ops/ms
Iteration   2: 11.255 ops/ms
Iteration   3: 11.393 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.313 ±(99.9%) 1.296 ops/ms [Average]
  (min, avg, max) = (11.255, 11.313, 11.393), stdev = 0.071
  CI (99.9%): [10.017, 12.610] (assumes normal distribution)


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
# Warmup Iteration   1: 7.235 ops/ms
# Warmup Iteration   2: 10.346 ops/ms
# Warmup Iteration   3: 10.835 ops/ms
Iteration   1: 10.760 ops/ms
Iteration   2: 10.800 ops/ms
Iteration   3: 10.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.841 ±(99.9%) 1.959 ops/ms [Average]
  (min, avg, max) = (10.760, 10.841, 10.963), stdev = 0.107
  CI (99.9%): [8.882, 12.800] (assumes normal distribution)


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
# Warmup Iteration   1: 6.302 ops/ms
# Warmup Iteration   2: 8.215 ops/ms
# Warmup Iteration   3: 8.516 ops/ms
Iteration   1: 8.358 ops/ms
Iteration   2: 8.736 ops/ms
Iteration   3: 8.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.610 ±(99.9%) 3.991 ops/ms [Average]
  (min, avg, max) = (8.358, 8.610, 8.737), stdev = 0.219
  CI (99.9%): [4.619, 12.601] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 2.967 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.980 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.967, 2.980, 2.988), stdev = 0.012
  CI (99.9%): [2.761, 3.200] (assumes normal distribution)


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
# Warmup Iteration   1: 3.834 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.954 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.869 ±(99.9%) 0.003 ms/op
Iteration   1: 2.849 ±(99.9%) 0.003 ms/op
Iteration   2: 2.809 ±(99.9%) 0.003 ms/op
Iteration   3: 2.818 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.825 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (2.809, 2.825, 2.849), stdev = 0.021
  CI (99.9%): [2.442, 3.209] (assumes normal distribution)


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.003 ms/op
Iteration   1: 2.946 ±(99.9%) 0.003 ms/op
Iteration   2: 2.937 ±(99.9%) 0.004 ms/op
Iteration   3: 2.906 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.930 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (2.906, 2.930, 2.946), stdev = 0.021
  CI (99.9%): [2.541, 3.318] (assumes normal distribution)


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
# Warmup Iteration   1: 4.093 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.011 ms/op
Iteration   1: 3.891 ±(99.9%) 0.006 ms/op
Iteration   2: 3.784 ±(99.9%) 0.011 ms/op
Iteration   3: 3.805 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.827 ±(99.9%) 1.038 ms/op [Average]
  (min, avg, max) = (3.784, 3.827, 3.891), stdev = 0.057
  CI (99.9%): [2.789, 4.864] (assumes normal distribution)


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
# Warmup Iteration   1: 3.987 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
Iteration   1: 2.976 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  6.963 ms/op
                 createUser·p0.9999: 11.625 ms/op
                 createUser·p1.00:   12.468 ms/op

Iteration   2: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  11.471 ms/op
                 createUser·p0.9999: 15.782 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.285 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  13.735 ms/op
                 createUser·p0.9999: 19.904 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319013
  mean =      3.010 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30006 
    [ 2.500,  5.000) = 287467 
    [ 5.000,  7.500) = 996 
    [ 7.500, 10.000) = 243 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      9.732 ms/op
     p(99.9900) =     19.376 ms/op
     p(99.9990) =     20.134 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.822 ±(99.9%) 0.005 ms/op
Iteration   1: 2.819 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.596 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.913 ms/op
                 existUser·p0.9999: 27.274 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   2: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  6.119 ms/op
                 existUser·p0.9999: 14.618 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   3: 2.874 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.629 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.671 ms/op
                 existUser·p0.9999: 17.031 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334047
  mean =      2.872 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51547 
    [ 2.500,  5.000) = 281615 
    [ 5.000,  7.500) = 631 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.733 ms/op
     p(99.9900) =     20.355 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 3.872 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.006 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  7.225 ms/op
                 getUser·p0.9999: 17.531 ms/op
                 getUser·p1.00:   18.678 ms/op

Iteration   2: 2.951 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.718 ms/op
                 getUser·p0.9999: 12.899 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   3: 2.941 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.555 ms/op
                 getUser·p0.9999: 24.412 ms/op
                 getUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325976
  mean =      2.945 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30111 
    [ 2.500,  5.000) = 294495 
    [ 5.000,  7.500) = 1105 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      7.274 ms/op
     p(99.9900) =     20.101 ms/op
     p(99.9990) =     24.436 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 5.229 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.915 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.010 ms/op
Iteration   1: 3.841 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  12.517 ms/op
                 listUser·p0.9999: 14.046 ms/op
                 listUser·p1.00:   14.942 ms/op

Iteration   2: 3.797 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 25.938 ms/op
                 listUser·p1.00:   26.378 ms/op

Iteration   3: 3.838 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.698 ms/op
                 listUser·p0.999:  17.847 ms/op
                 listUser·p0.9999: 22.850 ms/op
                 listUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250964
  mean =      3.826 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7865 
    [ 2.500,  5.000) = 221560 
    [ 5.000,  7.500) = 20377 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     15.042 ms/op
     p(99.9900) =     25.163 ms/op
     p(99.9990) =     26.230 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.718 ± 1.597  ops/ms
ClientGrpc.existUser                       thrpt       3  11.313 ± 1.296  ops/ms
ClientGrpc.getUser                         thrpt       3  10.841 ± 1.959  ops/ms
ClientGrpc.listUser                        thrpt       3   8.610 ± 3.991  ops/ms
ClientGrpc.createUser                       avgt       3   2.980 ± 0.219   ms/op
ClientGrpc.existUser                        avgt       3   2.825 ± 0.383   ms/op
ClientGrpc.getUser                          avgt       3   2.930 ± 0.389   ms/op
ClientGrpc.listUser                         avgt       3   3.827 ± 1.038   ms/op
ClientGrpc.createUser                     sample  319013   3.010 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.285           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.732           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.376           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.251           ms/op
ClientGrpc.existUser                      sample  334047   2.872 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.573           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.733           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.355           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.492           ms/op
ClientGrpc.getUser                        sample  325976   2.945 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.613           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.274           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.101           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.510           ms/op
ClientGrpc.listUser                       sample  250964   3.826 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.077           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.677           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.042           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.163           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.378           ms/op
