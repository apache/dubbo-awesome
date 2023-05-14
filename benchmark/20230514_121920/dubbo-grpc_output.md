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
# Warmup Iteration   1: 3.215 ops/ms
# Warmup Iteration   2: 7.241 ops/ms
# Warmup Iteration   3: 8.650 ops/ms
Iteration   1: 9.156 ops/ms
Iteration   2: 8.970 ops/ms
Iteration   3: 9.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.042 ±(99.9%) 1.816 ops/ms [Average]
  (min, avg, max) = (8.970, 9.042, 9.156), stdev = 0.100
  CI (99.9%): [7.227, 10.858] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.453 ops/ms
# Warmup Iteration   2: 8.568 ops/ms
# Warmup Iteration   3: 9.407 ops/ms
Iteration   1: 9.520 ops/ms
Iteration   2: 9.608 ops/ms
Iteration   3: 9.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.580 ±(99.9%) 0.951 ops/ms [Average]
  (min, avg, max) = (9.520, 9.580, 9.613), stdev = 0.052
  CI (99.9%): [8.630, 10.531] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.509 ops/ms
# Warmup Iteration   2: 8.744 ops/ms
# Warmup Iteration   3: 8.971 ops/ms
Iteration   1: 9.085 ops/ms
Iteration   2: 8.992 ops/ms
Iteration   3: 9.328 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.135 ±(99.9%) 3.167 ops/ms [Average]
  (min, avg, max) = (8.992, 9.135, 9.328), stdev = 0.174
  CI (99.9%): [5.968, 12.302] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.980 ops/ms
# Warmup Iteration   2: 6.333 ops/ms
# Warmup Iteration   3: 6.627 ops/ms
Iteration   1: 6.841 ops/ms
Iteration   2: 6.891 ops/ms
Iteration   3: 6.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.848 ±(99.9%) 0.713 ops/ms [Average]
  (min, avg, max) = (6.814, 6.848, 6.891), stdev = 0.039
  CI (99.9%): [6.135, 7.562] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.972 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.003 ms/op
Iteration   1: 3.498 ±(99.9%) 0.003 ms/op
Iteration   2: 3.577 ±(99.9%) 0.002 ms/op
Iteration   3: 3.512 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.529 ±(99.9%) 0.772 ms/op [Average]
  (min, avg, max) = (3.498, 3.529, 3.577), stdev = 0.042
  CI (99.9%): [2.757, 4.301] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.464 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.004 ms/op
Iteration   1: 3.248 ±(99.9%) 0.003 ms/op
Iteration   2: 3.331 ±(99.9%) 0.004 ms/op
Iteration   3: 3.356 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.312 ±(99.9%) 1.027 ms/op [Average]
  (min, avg, max) = (3.248, 3.312, 3.356), stdev = 0.056
  CI (99.9%): [2.285, 4.339] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.038 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.757 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.580 ±(99.9%) 0.004 ms/op
Iteration   1: 3.565 ±(99.9%) 0.007 ms/op
Iteration   2: 3.460 ±(99.9%) 0.003 ms/op
Iteration   3: 3.474 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.500 ±(99.9%) 1.041 ms/op [Average]
  (min, avg, max) = (3.460, 3.500, 3.565), stdev = 0.057
  CI (99.9%): [2.459, 4.540] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.173 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.958 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.728 ±(99.9%) 0.023 ms/op
Iteration   1: 4.708 ±(99.9%) 0.012 ms/op
Iteration   2: 4.588 ±(99.9%) 0.018 ms/op
Iteration   3: 4.650 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.649 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (4.588, 4.649, 4.708), stdev = 0.060
  CI (99.9%): [3.552, 5.745] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.889 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.007 ms/op
Iteration   1: 3.511 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  7.765 ms/op
                 createUser·p0.9999: 15.428 ms/op
                 createUser·p1.00:   15.811 ms/op

Iteration   2: 3.555 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  10.858 ms/op
                 createUser·p0.9999: 16.728 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   3: 3.498 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  8.151 ms/op
                 createUser·p0.9999: 19.357 ms/op
                 createUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 272662
  mean =      3.521 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 102 
    [ 1.250,  2.500) = 7708 
    [ 2.500,  3.750) = 192506 
    [ 3.750,  5.000) = 67950 
    [ 5.000,  6.250) = 3198 
    [ 6.250,  7.500) = 583 
    [ 7.500,  8.750) = 248 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 93 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     10.065 ms/op
     p(99.9900) =     18.440 ms/op
     p(99.9990) =     19.530 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.982 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.008 ms/op
Iteration   1: 3.484 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.982 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.399 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  7.952 ms/op
                 existUser·p0.9999: 14.464 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   2: 3.488 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.867 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   5.606 ms/op
                 existUser·p0.999:  9.688 ms/op
                 existUser·p0.9999: 16.439 ms/op
                 existUser·p1.00:   17.334 ms/op

Iteration   3: 3.419 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.866 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.171 ms/op
                 existUser·p0.999:  12.993 ms/op
                 existUser·p0.9999: 17.138 ms/op
                 existUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 277056
  mean =      3.464 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 309 
    [ 1.250,  2.500) = 7776 
    [ 2.500,  3.750) = 207816 
    [ 3.750,  5.000) = 57093 
    [ 5.000,  6.250) = 2847 
    [ 6.250,  7.500) = 568 
    [ 7.500,  8.750) = 227 
    [ 8.750, 10.000) = 160 
    [10.000, 11.250) = 45 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 64 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      9.764 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     18.544 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.532 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.008 ms/op
Iteration   1: 3.620 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.260 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 19.268 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   2: 3.549 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  8.487 ms/op
                 getUser·p0.9999: 17.137 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   3: 3.656 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.363 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.193 ms/op
                 getUser·p0.999:  12.668 ms/op
                 getUser·p0.9999: 20.259 ms/op
                 getUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 266137
  mean =      3.608 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9071 
    [ 2.500,  5.000) = 249343 
    [ 5.000,  7.500) = 6934 
    [ 7.500, 10.000) = 556 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.363 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =      9.648 ms/op
     p(99.9900) =     19.825 ms/op
     p(99.9990) =     21.424 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 5.786 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.272 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.895 ±(99.9%) 0.016 ms/op
Iteration   1: 4.820 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.308 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  15.821 ms/op
                 listUser·p0.9999: 19.379 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 4.794 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   8.667 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 20.775 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 4.866 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   9.106 ms/op
                 listUser·p0.999:  21.114 ms/op
                 listUser·p0.9999: 27.066 ms/op
                 listUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198985
  mean =      4.827 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 675 
    [ 2.500,  5.000) = 140569 
    [ 5.000,  7.500) = 51688 
    [ 7.500, 10.000) = 4990 
    [10.000, 12.500) = 645 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      6.947 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     26.706 ms/op
     p(99.9990) =     27.199 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.042 ± 1.816  ops/ms
ClientGrpc.existUser                       thrpt       3   9.580 ± 0.951  ops/ms
ClientGrpc.getUser                         thrpt       3   9.135 ± 3.167  ops/ms
ClientGrpc.listUser                        thrpt       3   6.848 ± 0.713  ops/ms
ClientGrpc.createUser                       avgt       3   3.529 ± 0.772   ms/op
ClientGrpc.existUser                        avgt       3   3.312 ± 1.027   ms/op
ClientGrpc.getUser                          avgt       3   3.500 ± 1.041   ms/op
ClientGrpc.listUser                         avgt       3   4.649 ± 1.096   ms/op
ClientGrpc.createUser                     sample  272662   3.521 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.821           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.490           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.059           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.065           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.440           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.792           ms/op
ClientGrpc.existUser                      sample  277056   3.464 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.866           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.051           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.341           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.764           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.072           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.711           ms/op
ClientGrpc.getUser                        sample  266137   3.608 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.363           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.906           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.648           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.825           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.086           ms/op
ClientGrpc.listUser                       sample  198985   4.827 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.077           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.193           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.929           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.105           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.706           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.361           ms/op
