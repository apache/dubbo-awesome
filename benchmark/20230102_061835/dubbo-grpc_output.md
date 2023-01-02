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
# Warmup Iteration   1: 3.685 ops/ms
# Warmup Iteration   2: 7.893 ops/ms
# Warmup Iteration   3: 9.000 ops/ms
Iteration   1: 9.593 ops/ms
Iteration   2: 9.131 ops/ms
Iteration   3: 9.205 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.309 ±(99.9%) 4.531 ops/ms [Average]
  (min, avg, max) = (9.131, 9.309, 9.593), stdev = 0.248
  CI (99.9%): [4.778, 13.841] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.567 ops/ms
# Warmup Iteration   2: 8.863 ops/ms
# Warmup Iteration   3: 9.311 ops/ms
Iteration   1: 9.538 ops/ms
Iteration   2: 9.586 ops/ms
Iteration   3: 9.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.634 ±(99.9%) 2.330 ops/ms [Average]
  (min, avg, max) = (9.538, 9.634, 9.779), stdev = 0.128
  CI (99.9%): [7.305, 11.964] (assumes normal distribution)


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
# Warmup Iteration   1: 6.050 ops/ms
# Warmup Iteration   2: 8.714 ops/ms
# Warmup Iteration   3: 8.989 ops/ms
Iteration   1: 8.988 ops/ms
Iteration   2: 9.076 ops/ms
Iteration   3: 9.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.076 ±(99.9%) 1.599 ops/ms [Average]
  (min, avg, max) = (8.988, 9.076, 9.164), stdev = 0.088
  CI (99.9%): [7.477, 10.675] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.033 ops/ms
# Warmup Iteration   2: 6.863 ops/ms
# Warmup Iteration   3: 7.037 ops/ms
Iteration   1: 6.933 ops/ms
Iteration   2: 7.053 ops/ms
Iteration   3: 7.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.036 ±(99.9%) 1.737 ops/ms [Average]
  (min, avg, max) = (6.933, 7.036, 7.121), stdev = 0.095
  CI (99.9%): [5.298, 8.773] (assumes normal distribution)


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
# Warmup Iteration   1: 4.973 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.527 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.010 ms/op
Iteration   1: 3.527 ±(99.9%) 0.002 ms/op
Iteration   2: 3.577 ±(99.9%) 0.002 ms/op
Iteration   3: 3.495 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.533 ±(99.9%) 0.752 ms/op [Average]
  (min, avg, max) = (3.495, 3.533, 3.577), stdev = 0.041
  CI (99.9%): [2.781, 4.285] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.621 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.521 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.003 ms/op
Iteration   1: 3.352 ±(99.9%) 0.002 ms/op
Iteration   2: 3.436 ±(99.9%) 0.003 ms/op
Iteration   3: 3.450 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.413 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (3.352, 3.413, 3.450), stdev = 0.053
  CI (99.9%): [2.449, 4.377] (assumes normal distribution)


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
# Warmup Iteration   1: 4.659 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.003 ms/op
Iteration   1: 3.494 ±(99.9%) 0.002 ms/op
Iteration   2: 3.587 ±(99.9%) 0.002 ms/op
Iteration   3: 3.532 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.538 ±(99.9%) 0.855 ms/op [Average]
  (min, avg, max) = (3.494, 3.538, 3.587), stdev = 0.047
  CI (99.9%): [2.683, 4.393] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.360 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.649 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.511 ±(99.9%) 0.022 ms/op
Iteration   1: 4.627 ±(99.9%) 0.007 ms/op
Iteration   2: 4.411 ±(99.9%) 0.005 ms/op
Iteration   3: 4.600 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.546 ±(99.9%) 2.147 ms/op [Average]
  (min, avg, max) = (4.411, 4.546, 4.627), stdev = 0.118
  CI (99.9%): [2.399, 6.693] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.745 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.664 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.006 ms/op
Iteration   1: 3.394 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   5.199 ms/op
                 createUser·p0.999:  8.827 ms/op
                 createUser·p0.9999: 13.054 ms/op
                 createUser·p1.00:   13.435 ms/op

Iteration   2: 3.423 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  9.800 ms/op
                 createUser·p0.9999: 18.896 ms/op
                 createUser·p1.00:   19.366 ms/op

Iteration   3: 3.536 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  7.519 ms/op
                 createUser·p0.9999: 15.236 ms/op
                 createUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 278268
  mean =      3.450 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 312 
    [ 1.250,  2.500) = 8300 
    [ 2.500,  3.750) = 207459 
    [ 3.750,  5.000) = 59257 
    [ 5.000,  6.250) = 2142 
    [ 6.250,  7.500) = 349 
    [ 7.500,  8.750) = 150 
    [ 8.750, 10.000) = 94 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.408 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.022 ms/op
     p(99.9000) =      8.941 ms/op
     p(99.9900) =     17.760 ms/op
     p(99.9990) =     19.333 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.580 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.505 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.007 ms/op
Iteration   1: 3.433 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.783 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  7.356 ms/op
                 existUser·p0.9999: 17.357 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   2: 3.373 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.624 ms/op
                 existUser·p0.50:   3.391 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   4.760 ms/op
                 existUser·p0.999:  9.559 ms/op
                 existUser·p0.9999: 13.239 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   3: 3.406 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.419 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   4.084 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  7.397 ms/op
                 existUser·p0.9999: 16.518 ms/op
                 existUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 282005
  mean =      3.404 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1176 
    [ 1.250,  2.500) = 13180 
    [ 2.500,  3.750) = 192501 
    [ 3.750,  5.000) = 73822 
    [ 5.000,  6.250) = 771 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 55 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.419 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      8.061 ms/op
     p(99.9900) =     16.735 ms/op
     p(99.9990) =     17.668 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 4.769 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.509 ±(99.9%) 0.009 ms/op
Iteration   1: 3.485 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.461 ms/op
                 getUser·p0.90:   4.219 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  9.846 ms/op
                 getUser·p0.9999: 14.399 ms/op
                 getUser·p1.00:   16.105 ms/op

Iteration   2: 3.376 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   3.363 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   4.719 ms/op
                 getUser·p0.999:  6.791 ms/op
                 getUser·p0.9999: 16.991 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 3.432 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.909 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.035 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   4.743 ms/op
                 getUser·p0.999:  7.213 ms/op
                 getUser·p0.9999: 18.536 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 279815
  mean =      3.431 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9289 
    [ 2.500,  5.000) = 268482 
    [ 5.000,  7.500) = 1714 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.404 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      4.866 ms/op
     p(99.9000) =      7.818 ms/op
     p(99.9900) =     18.220 ms/op
     p(99.9990) =     20.041 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


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
# Warmup Iteration   1: 6.148 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.669 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.473 ±(99.9%) 0.013 ms/op
Iteration   1: 4.531 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.250 ms/op
                 listUser·p0.99:   7.627 ms/op
                 listUser·p0.999:  14.602 ms/op
                 listUser·p0.9999: 20.904 ms/op
                 listUser·p1.00:   22.741 ms/op

Iteration   2: 4.449 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   4.235 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  13.945 ms/op
                 listUser·p0.9999: 17.256 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 4.586 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.180 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   7.713 ms/op
                 listUser·p0.999:  15.049 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 212313
  mean =      4.521 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 779 
    [ 2.500,  5.000) = 163051 
    [ 5.000,  7.500) = 45908 
    [ 7.500, 10.000) = 2148 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     14.855 ms/op
     p(99.9900) =     19.653 ms/op
     p(99.9990) =     22.251 ms/op
     p(99.9999) =     22.741 ms/op
    p(100.0000) =     22.741 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.309 ± 4.531  ops/ms
ClientGrpc.existUser                       thrpt       3   9.634 ± 2.330  ops/ms
ClientGrpc.getUser                         thrpt       3   9.076 ± 1.599  ops/ms
ClientGrpc.listUser                        thrpt       3   7.036 ± 1.737  ops/ms
ClientGrpc.createUser                       avgt       3   3.533 ± 0.752   ms/op
ClientGrpc.existUser                        avgt       3   3.413 ± 0.964   ms/op
ClientGrpc.getUser                          avgt       3   3.538 ± 0.855   ms/op
ClientGrpc.listUser                         avgt       3   4.546 ± 2.147   ms/op
ClientGrpc.createUser                     sample  278268   3.450 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.752           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.408           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.084           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.022           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.941           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.760           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.366           ms/op
ClientGrpc.existUser                      sample  282005   3.404 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.419           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.404           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.350           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.727           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.061           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.735           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.793           ms/op
ClientGrpc.getUser                        sample  279815   3.431 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.687           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.404           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.063           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.866           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.818           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.220           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.185           ms/op
ClientGrpc.listUser                       sample  212313   4.521 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.124           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.301           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.825           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.651           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.855           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.653           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.741           ms/op
