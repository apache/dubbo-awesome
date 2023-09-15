# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.550 ops/ms
# Warmup Iteration   2: 7.610 ops/ms
# Warmup Iteration   3: 8.587 ops/ms
Iteration   1: 9.127 ops/ms
Iteration   2: 9.113 ops/ms
Iteration   3: 9.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.080 ±(99.9%) 1.242 ops/ms [Average]
  (min, avg, max) = (9.002, 9.080, 9.127), stdev = 0.068
  CI (99.9%): [7.839, 10.322] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.159 ops/ms
# Warmup Iteration   2: 9.135 ops/ms
# Warmup Iteration   3: 9.260 ops/ms
Iteration   1: 9.388 ops/ms
Iteration   2: 9.365 ops/ms
Iteration   3: 9.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.461 ±(99.9%) 2.690 ops/ms [Average]
  (min, avg, max) = (9.365, 9.461, 9.631), stdev = 0.147
  CI (99.9%): [6.771, 12.151] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.763 ops/ms
# Warmup Iteration   2: 8.738 ops/ms
# Warmup Iteration   3: 8.974 ops/ms
Iteration   1: 9.129 ops/ms
Iteration   2: 9.013 ops/ms
Iteration   3: 9.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.076 ±(99.9%) 1.072 ops/ms [Average]
  (min, avg, max) = (9.013, 9.076, 9.129), stdev = 0.059
  CI (99.9%): [8.004, 10.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.764 ops/ms
# Warmup Iteration   2: 6.817 ops/ms
# Warmup Iteration   3: 7.248 ops/ms
Iteration   1: 7.326 ops/ms
Iteration   2: 7.267 ops/ms
Iteration   3: 7.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.340 ±(99.9%) 1.460 ops/ms [Average]
  (min, avg, max) = (7.267, 7.340, 7.426), stdev = 0.080
  CI (99.9%): [5.880, 8.800] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.969 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.007 ms/op
Iteration   1: 3.532 ±(99.9%) 0.002 ms/op
Iteration   2: 3.549 ±(99.9%) 0.002 ms/op
Iteration   3: 3.665 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.582 ±(99.9%) 1.319 ms/op [Average]
  (min, avg, max) = (3.532, 3.582, 3.665), stdev = 0.072
  CI (99.9%): [2.263, 4.901] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.860 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.003 ms/op
Iteration   1: 3.394 ±(99.9%) 0.002 ms/op
Iteration   2: 3.458 ±(99.9%) 0.002 ms/op
Iteration   3: 3.402 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.418 ±(99.9%) 0.639 ms/op [Average]
  (min, avg, max) = (3.394, 3.418, 3.458), stdev = 0.035
  CI (99.9%): [2.779, 4.057] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 4.542 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.002 ms/op
Iteration   1: 3.540 ±(99.9%) 0.005 ms/op
Iteration   2: 3.611 ±(99.9%) 0.002 ms/op
Iteration   3: 3.466 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.539 ±(99.9%) 1.325 ms/op [Average]
  (min, avg, max) = (3.466, 3.539, 3.611), stdev = 0.073
  CI (99.9%): [2.214, 4.864] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.466 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.582 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.008 ms/op
Iteration   1: 4.481 ±(99.9%) 0.032 ms/op
Iteration   2: 4.419 ±(99.9%) 0.022 ms/op
Iteration   3: 4.212 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.371 ±(99.9%) 2.574 ms/op [Average]
  (min, avg, max) = (4.212, 4.371, 4.481), stdev = 0.141
  CI (99.9%): [1.797, 6.944] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.088 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.584 ±(99.9%) 0.008 ms/op
Iteration   1: 3.574 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.654 ms/op
                 createUser·p0.50:   3.498 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  9.380 ms/op
                 createUser·p0.9999: 13.880 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 3.524 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.478 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   4.981 ms/op
                 createUser·p0.999:  8.412 ms/op
                 createUser·p0.9999: 14.482 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   3: 3.476 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.412 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.295 ms/op
                 createUser·p0.999:  14.183 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 272350
  mean =      3.524 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 81 
    [ 1.250,  2.500) = 3159 
    [ 2.500,  3.750) = 192693 
    [ 3.750,  5.000) = 72911 
    [ 5.000,  6.250) = 2200 
    [ 6.250,  7.500) = 564 
    [ 7.500,  8.750) = 304 
    [ 8.750, 10.000) = 143 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     10.224 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     18.541 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.399 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.454 ±(99.9%) 0.007 ms/op
Iteration   1: 3.404 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.990 ms/op
                 existUser·p0.95:   4.162 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.857 ms/op
                 existUser·p0.9999: 18.881 ms/op
                 existUser·p1.00:   19.857 ms/op

Iteration   2: 3.413 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   4.006 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.006 ms/op
                 existUser·p0.999:  8.671 ms/op
                 existUser·p0.9999: 14.281 ms/op
                 existUser·p1.00:   15.761 ms/op

Iteration   3: 3.401 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  11.895 ms/op
                 existUser·p0.9999: 19.851 ms/op
                 existUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 281647
  mean =      3.406 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4462 
    [ 2.500,  5.000) = 274384 
    [ 5.000,  7.500) = 2029 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =     10.770 ms/op
     p(99.9900) =     19.377 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.105 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.009 ms/op
Iteration   1: 3.554 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.502 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.342 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   2: 3.521 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.323 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  8.020 ms/op
                 getUser·p0.9999: 17.168 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   3: 3.465 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.416 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   5.120 ms/op
                 getUser·p0.999:  7.209 ms/op
                 getUser·p0.9999: 19.333 ms/op
                 getUser·p1.00:   19.825 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 273133
  mean =      3.513 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 3428 
    [ 2.500,  3.750) = 192906 
    [ 3.750,  5.000) = 73599 
    [ 5.000,  6.250) = 2059 
    [ 6.250,  7.500) = 592 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.323 ms/op
     p(50.0000) =      3.465 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =      8.716 ms/op
     p(99.9900) =     17.357 ms/op
     p(99.9990) =     19.735 ms/op
     p(99.9999) =     19.825 ms/op
    p(100.0000) =     19.825 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.205 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.606 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.367 ±(99.9%) 0.010 ms/op
Iteration   1: 4.446 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   4.317 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   6.362 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  14.223 ms/op
                 listUser·p0.9999: 18.029 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 4.394 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.455 ms/op
                 listUser·p0.999:  15.388 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   3: 4.375 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.780 ms/op
                 listUser·p0.50:   4.268 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 20.099 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 217873
  mean =      4.405 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 508 
    [ 2.500,  5.000) = 195250 
    [ 5.000,  7.500) = 19959 
    [ 7.500, 10.000) = 1596 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 99 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      4.293 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     15.417 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     20.835 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.080 ± 1.242  ops/ms
ClientGrpc.existUser                       thrpt       3   9.461 ± 2.690  ops/ms
ClientGrpc.getUser                         thrpt       3   9.076 ± 1.072  ops/ms
ClientGrpc.listUser                        thrpt       3   7.340 ± 1.460  ops/ms
ClientGrpc.createUser                       avgt       3   3.582 ± 1.319   ms/op
ClientGrpc.existUser                        avgt       3   3.418 ± 0.639   ms/op
ClientGrpc.getUser                          avgt       3   3.539 ± 1.325   ms/op
ClientGrpc.listUser                         avgt       3   4.371 ± 2.574   ms/op
ClientGrpc.createUser                     sample  272350   3.524 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.654           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.259           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.224           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.859           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.809           ms/op
ClientGrpc.existUser                      sample  281647   3.406 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.997           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.770           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.377           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.251           ms/op
ClientGrpc.getUser                        sample  273133   3.513 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.323           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.108           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.120           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.716           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.357           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.825           ms/op
ClientGrpc.listUser                       sample  217873   4.405 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.780           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.293           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.496           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.417           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.661           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.873           ms/op
