# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.579 ops/ms
# Warmup Iteration   2: 8.867 ops/ms
# Warmup Iteration   3: 10.194 ops/ms
Iteration   1: 10.580 ops/ms
Iteration   2: 10.492 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.523 ±(99.9%) 0.894 ops/ms [Average]
  (min, avg, max) = (10.492, 10.523, 10.580), stdev = 0.049
  CI (99.9%): [9.629, 11.417] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.687 ops/ms
# Warmup Iteration   2: 10.457 ops/ms
# Warmup Iteration   3: 10.768 ops/ms
Iteration   1: 10.600 ops/ms
Iteration   2: 10.744 ops/ms
Iteration   3: 10.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.630 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (10.547, 10.630, 10.744), stdev = 0.102
  CI (99.9%): [8.768, 12.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.041 ops/ms
# Warmup Iteration   2: 10.080 ops/ms
# Warmup Iteration   3: 10.573 ops/ms
Iteration   1: 10.572 ops/ms
Iteration   2: 10.500 ops/ms
Iteration   3: 9.896 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.323 ±(99.9%) 6.772 ops/ms [Average]
  (min, avg, max) = (9.896, 10.323, 10.572), stdev = 0.371
  CI (99.9%): [3.550, 17.095] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.374 ops/ms
# Warmup Iteration   2: 7.951 ops/ms
# Warmup Iteration   3: 8.048 ops/ms
Iteration   1: 7.828 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 7.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.884 ±(99.9%) 1.031 ops/ms [Average]
  (min, avg, max) = (7.828, 7.884, 7.941), stdev = 0.057
  CI (99.9%): [6.853, 8.915] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.046 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.002 ms/op
Iteration   1: 3.223 ±(99.9%) 0.002 ms/op
Iteration   2: 3.123 ±(99.9%) 0.002 ms/op
Iteration   3: 3.084 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.144 ±(99.9%) 1.309 ms/op [Average]
  (min, avg, max) = (3.084, 3.144, 3.223), stdev = 0.072
  CI (99.9%): [1.834, 4.453] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.529 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 2.976 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.002 ms/op
Iteration   1: 3.063 ±(99.9%) 0.002 ms/op
Iteration   2: 3.015 ±(99.9%) 0.002 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.028 ±(99.9%) 0.554 ms/op [Average]
  (min, avg, max) = (3.007, 3.028, 3.063), stdev = 0.030
  CI (99.9%): [2.474, 3.582] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.886 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.002 ms/op
Iteration   1: 3.114 ±(99.9%) 0.002 ms/op
Iteration   2: 3.185 ±(99.9%) 0.002 ms/op
Iteration   3: 3.103 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.134 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.103, 3.134, 3.185), stdev = 0.045
  CI (99.9%): [2.319, 3.949] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.897 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.021 ms/op
Iteration   1: 3.978 ±(99.9%) 0.034 ms/op
Iteration   2: 3.897 ±(99.9%) 0.018 ms/op
Iteration   3: 3.838 ±(99.9%) 0.048 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.905 ±(99.9%) 1.280 ms/op [Average]
  (min, avg, max) = (3.838, 3.905, 3.978), stdev = 0.070
  CI (99.9%): [2.625, 5.185] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.934 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.545 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.398 ms/op
                 createUser·p0.999:  6.523 ms/op
                 createUser·p0.9999: 11.553 ms/op
                 createUser·p1.00:   12.173 ms/op

Iteration   2: 3.005 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.483 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.361 ms/op
                 createUser·p0.9999: 12.219 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   3: 2.884 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.429 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.518 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  12.153 ms/op
                 createUser·p0.9999: 17.658 ms/op
                 createUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323254
  mean =      2.971 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4604 
    [ 1.250,  2.500) = 28577 
    [ 2.500,  3.750) = 278006 
    [ 3.750,  5.000) = 11136 
    [ 5.000,  6.250) = 511 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 46 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.429 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.055 ms/op
     p(99.9900) =     14.697 ms/op
     p(99.9990) =     17.891 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.003 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
Iteration   1: 2.988 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  5.789 ms/op
                 existUser·p0.9999: 21.210 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   2: 2.909 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.688 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  6.250 ms/op
                 existUser·p0.9999: 30.834 ms/op
                 existUser·p1.00:   32.113 ms/op

Iteration   3: 2.892 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.618 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  9.165 ms/op
                 existUser·p0.9999: 22.510 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327889
  mean =      2.929 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52359 
    [ 2.500,  5.000) = 274678 
    [ 5.000,  7.500) = 594 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      6.472 ms/op
     p(99.9900) =     25.786 ms/op
     p(99.9990) =     32.005 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.319 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.115 ±(99.9%) 0.007 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.831 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.646 ms/op
                 getUser·p0.9999: 17.899 ms/op
                 getUser·p1.00:   18.317 ms/op

Iteration   2: 2.982 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.260 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.642 ms/op
                 getUser·p0.9999: 19.694 ms/op
                 getUser·p1.00:   19.923 ms/op

Iteration   3: 3.107 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.291 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  12.605 ms/op
                 getUser·p0.9999: 34.124 ms/op
                 getUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314201
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24771 
    [ 2.500,  5.000) = 288083 
    [ 5.000,  7.500) = 862 
    [ 7.500, 10.000) = 246 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.260 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      8.913 ms/op
     p(99.9900) =     32.132 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.747 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.200 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.012 ms/op
Iteration   1: 3.916 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.715 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  11.917 ms/op
                 listUser·p0.9999: 14.140 ms/op
                 listUser·p1.00:   15.696 ms/op

Iteration   2: 3.960 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 26.146 ms/op
                 listUser·p1.00:   30.179 ms/op

Iteration   3: 4.034 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  17.470 ms/op
                 listUser·p0.9999: 22.612 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241805
  mean =      3.969 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4285 
    [ 2.500,  5.000) = 207778 
    [ 5.000,  7.500) = 28455 
    [ 7.500, 10.000) = 813 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.715 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     14.794 ms/op
     p(99.9900) =     23.986 ms/op
     p(99.9990) =     30.083 ms/op
     p(99.9999) =     30.179 ms/op
    p(100.0000) =     30.179 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.523 ± 0.894  ops/ms
ClientGrpc.existUser                       thrpt       3  10.630 ± 1.863  ops/ms
ClientGrpc.getUser                         thrpt       3  10.323 ± 6.772  ops/ms
ClientGrpc.listUser                        thrpt       3   7.884 ± 1.031  ops/ms
ClientGrpc.createUser                       avgt       3   3.144 ± 1.309   ms/op
ClientGrpc.existUser                        avgt       3   3.028 ± 0.554   ms/op
ClientGrpc.getUser                          avgt       3   3.134 ± 0.815   ms/op
ClientGrpc.listUser                         avgt       3   3.905 ± 1.280   ms/op
ClientGrpc.createUser                     sample  323254   2.971 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.429           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.055           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.697           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.088           ms/op
ClientGrpc.existUser                      sample  327889   2.929 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.612           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.472           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.786           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.113           ms/op
ClientGrpc.getUser                        sample  314201   3.056 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.260           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.913           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.132           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.341           ms/op
ClientGrpc.listUser                       sample  241805   3.969 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.715           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.177           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.751           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.794           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.986           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.179           ms/op
