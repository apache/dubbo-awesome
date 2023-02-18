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
# Warmup Iteration   1: 3.781 ops/ms
# Warmup Iteration   2: 7.942 ops/ms
# Warmup Iteration   3: 9.190 ops/ms
Iteration   1: 9.443 ops/ms
Iteration   2: 9.551 ops/ms
Iteration   3: 9.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.424 ±(99.9%) 2.507 ops/ms [Average]
  (min, avg, max) = (9.278, 9.424, 9.551), stdev = 0.137
  CI (99.9%): [6.917, 11.932] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.736 ops/ms
# Warmup Iteration   2: 9.238 ops/ms
# Warmup Iteration   3: 10.059 ops/ms
Iteration   1: 9.848 ops/ms
Iteration   2: 9.868 ops/ms
Iteration   3: 9.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.864 ±(99.9%) 0.274 ops/ms [Average]
  (min, avg, max) = (9.848, 9.864, 9.877), stdev = 0.015
  CI (99.9%): [9.591, 10.138] (assumes normal distribution)


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
# Warmup Iteration   1: 6.292 ops/ms
# Warmup Iteration   2: 9.030 ops/ms
# Warmup Iteration   3: 9.314 ops/ms
Iteration   1: 9.094 ops/ms
Iteration   2: 9.088 ops/ms
Iteration   3: 9.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.202 ±(99.9%) 3.507 ops/ms [Average]
  (min, avg, max) = (9.088, 9.202, 9.424), stdev = 0.192
  CI (99.9%): [5.695, 12.709] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.510 ops/ms
# Warmup Iteration   2: 6.596 ops/ms
# Warmup Iteration   3: 6.713 ops/ms
Iteration   1: 7.183 ops/ms
Iteration   2: 7.107 ops/ms
Iteration   3: 7.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.152 ±(99.9%) 0.729 ops/ms [Average]
  (min, avg, max) = (7.107, 7.152, 7.183), stdev = 0.040
  CI (99.9%): [6.423, 7.881] (assumes normal distribution)


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
# Warmup Iteration   1: 4.581 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.003 ms/op
Iteration   1: 3.304 ±(99.9%) 0.002 ms/op
Iteration   2: 3.366 ±(99.9%) 0.003 ms/op
Iteration   3: 3.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.360 ±(99.9%) 0.977 ms/op [Average]
  (min, avg, max) = (3.304, 3.360, 3.410), stdev = 0.054
  CI (99.9%): [2.383, 4.336] (assumes normal distribution)


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.004 ms/op
Iteration   1: 3.305 ±(99.9%) 0.003 ms/op
Iteration   2: 3.166 ±(99.9%) 0.002 ms/op
Iteration   3: 3.177 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.216 ±(99.9%) 1.409 ms/op [Average]
  (min, avg, max) = (3.166, 3.216, 3.305), stdev = 0.077
  CI (99.9%): [1.807, 4.625] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.521 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.506 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.004 ms/op
Iteration   1: 3.329 ±(99.9%) 0.004 ms/op
Iteration   2: 3.517 ±(99.9%) 0.003 ms/op
Iteration   3: 3.533 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.460 ±(99.9%) 2.071 ms/op [Average]
  (min, avg, max) = (3.329, 3.460, 3.533), stdev = 0.113
  CI (99.9%): [1.389, 5.530] (assumes normal distribution)


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
# Warmup Iteration   1: 6.105 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.533 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.399 ±(99.9%) 0.017 ms/op
Iteration   1: 4.374 ±(99.9%) 0.032 ms/op
Iteration   2: 4.434 ±(99.9%) 0.025 ms/op
Iteration   3: 4.380 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.396 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (4.374, 4.396, 4.434), stdev = 0.033
  CI (99.9%): [3.789, 5.003] (assumes normal distribution)


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
# Warmup Iteration   1: 5.006 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.762 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.009 ms/op
Iteration   1: 3.471 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.329 ms/op
                 createUser·p0.50:   3.416 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  13.217 ms/op
                 createUser·p0.9999: 15.239 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   2: 3.484 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  8.321 ms/op
                 createUser·p0.9999: 19.753 ms/op
                 createUser·p1.00:   21.692 ms/op

Iteration   3: 3.550 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  17.601 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 274121
  mean =      3.501 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9721 
    [ 2.500,  5.000) = 260350 
    [ 5.000,  7.500) = 3337 
    [ 7.500, 10.000) = 455 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.329 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.202 ms/op
     p(99.9000) =      9.814 ms/op
     p(99.9900) =     23.861 ms/op
     p(99.9990) =     25.421 ms/op
     p(99.9999) =     25.952 ms/op
    p(100.0000) =     25.952 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.377 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.430 ±(99.9%) 0.009 ms/op
Iteration   1: 3.348 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  7.512 ms/op
                 existUser·p0.9999: 15.284 ms/op
                 existUser·p1.00:   15.483 ms/op

Iteration   2: 3.321 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  7.996 ms/op
                 existUser·p0.9999: 13.982 ms/op
                 existUser·p1.00:   16.237 ms/op

Iteration   3: 3.343 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   4.964 ms/op
                 existUser·p0.999:  8.602 ms/op
                 existUser·p0.9999: 18.462 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 287808
  mean =      3.337 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 757 
    [ 1.250,  2.500) = 23217 
    [ 2.500,  3.750) = 192484 
    [ 3.750,  5.000) = 68415 
    [ 5.000,  6.250) = 2089 
    [ 6.250,  7.500) = 472 
    [ 7.500,  8.750) = 155 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.318 ms/op
     p(90.0000) =      4.145 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =      7.979 ms/op
     p(99.9900) =     16.948 ms/op
     p(99.9990) =     18.743 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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
# Warmup Iteration   1: 4.708 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.008 ms/op
Iteration   1: 3.223 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.768 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.243 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  7.592 ms/op
                 getUser·p0.9999: 19.237 ms/op
                 getUser·p1.00:   19.497 ms/op

Iteration   2: 3.381 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.830 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   4.948 ms/op
                 getUser·p0.999:  7.018 ms/op
                 getUser·p0.9999: 17.269 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   3: 3.455 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.913 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  7.974 ms/op
                 getUser·p0.9999: 23.290 ms/op
                 getUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 286371
  mean =      3.350 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23743 
    [ 2.500,  5.000) = 259723 
    [ 5.000,  7.500) = 2600 
    [ 7.500, 10.000) = 127 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.005 ms/op
     p(99.9000) =      7.583 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     23.536 ms/op
     p(99.9999) =     23.691 ms/op
    p(100.0000) =     23.691 ms/op


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
# Warmup Iteration   1: 6.214 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.347 ±(99.9%) 0.015 ms/op
Iteration   1: 4.253 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   4.080 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.226 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  16.227 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   21.004 ms/op

Iteration   2: 4.263 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.913 ms/op
                 listUser·p0.50:   4.092 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.083 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  20.742 ms/op
                 listUser·p0.9999: 29.082 ms/op
                 listUser·p1.00:   29.426 ms/op

Iteration   3: 4.339 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   4.129 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   6.193 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 21.435 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 223887
  mean =      4.285 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2057 
    [ 2.500,  5.000) = 185279 
    [ 5.000,  7.500) = 33968 
    [ 7.500, 10.000) = 2008 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 170 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      4.096 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      6.169 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     17.240 ms/op
     p(99.9900) =     28.213 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.426 ms/op
    p(100.0000) =     29.426 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.424 ± 2.507  ops/ms
ClientGrpc.existUser                       thrpt       3   9.864 ± 0.274  ops/ms
ClientGrpc.getUser                         thrpt       3   9.202 ± 3.507  ops/ms
ClientGrpc.listUser                        thrpt       3   7.152 ± 0.729  ops/ms
ClientGrpc.createUser                       avgt       3   3.360 ± 0.977   ms/op
ClientGrpc.existUser                        avgt       3   3.216 ± 1.409   ms/op
ClientGrpc.getUser                          avgt       3   3.460 ± 2.071   ms/op
ClientGrpc.listUser                         avgt       3   4.396 ± 0.607   ms/op
ClientGrpc.createUser                     sample  274121   3.501 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.329           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.478           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.153           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.814           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.861           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.952           ms/op
ClientGrpc.existUser                      sample  287808   3.337 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.671           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.318           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.014           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.979           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.948           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.809           ms/op
ClientGrpc.getUser                        sample  286371   3.350 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.768           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.314           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.170           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.005           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.583           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.692           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.691           ms/op
ClientGrpc.listUser                       sample  223887   4.285 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.781           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.096           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.169           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.635           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.240           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.213           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.426           ms/op
