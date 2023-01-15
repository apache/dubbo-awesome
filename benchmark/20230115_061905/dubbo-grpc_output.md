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
# Warmup Iteration   1: 3.297 ops/ms
# Warmup Iteration   2: 7.524 ops/ms
# Warmup Iteration   3: 8.667 ops/ms
Iteration   1: 9.216 ops/ms
Iteration   2: 8.948 ops/ms
Iteration   3: 8.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.042 ±(99.9%) 2.754 ops/ms [Average]
  (min, avg, max) = (8.948, 9.042, 9.216), stdev = 0.151
  CI (99.9%): [6.288, 11.796] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.570 ops/ms
# Warmup Iteration   2: 9.006 ops/ms
# Warmup Iteration   3: 9.219 ops/ms
Iteration   1: 9.236 ops/ms
Iteration   2: 9.321 ops/ms
Iteration   3: 9.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.265 ±(99.9%) 0.876 ops/ms [Average]
  (min, avg, max) = (9.236, 9.265, 9.321), stdev = 0.048
  CI (99.9%): [8.389, 10.141] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.948 ops/ms
# Warmup Iteration   2: 8.704 ops/ms
# Warmup Iteration   3: 8.895 ops/ms
Iteration   1: 8.777 ops/ms
Iteration   2: 8.979 ops/ms
Iteration   3: 9.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.006 ±(99.9%) 4.439 ops/ms [Average]
  (min, avg, max) = (8.777, 9.006, 9.261), stdev = 0.243
  CI (99.9%): [4.567, 13.444] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.495 ops/ms
# Warmup Iteration   2: 6.678 ops/ms
# Warmup Iteration   3: 6.882 ops/ms
Iteration   1: 6.978 ops/ms
Iteration   2: 7.394 ops/ms
Iteration   3: 7.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.170 ±(99.9%) 3.832 ops/ms [Average]
  (min, avg, max) = (6.978, 7.170, 7.394), stdev = 0.210
  CI (99.9%): [3.338, 11.002] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.798 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.005 ms/op
Iteration   1: 3.831 ±(99.9%) 0.003 ms/op
Iteration   2: 3.660 ±(99.9%) 0.002 ms/op
Iteration   3: 3.771 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.754 ±(99.9%) 1.588 ms/op [Average]
  (min, avg, max) = (3.660, 3.754, 3.831), stdev = 0.087
  CI (99.9%): [2.166, 5.342] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.654 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.657 ±(99.9%) 0.003 ms/op
Iteration   1: 3.433 ±(99.9%) 0.004 ms/op
Iteration   2: 3.530 ±(99.9%) 0.003 ms/op
Iteration   3: 3.440 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.468 ±(99.9%) 0.987 ms/op [Average]
  (min, avg, max) = (3.433, 3.468, 3.530), stdev = 0.054
  CI (99.9%): [2.481, 4.454] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.342 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.719 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.003 ms/op
Iteration   1: 3.626 ±(99.9%) 0.003 ms/op
Iteration   2: 3.634 ±(99.9%) 0.003 ms/op
Iteration   3: 3.657 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.639 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (3.626, 3.639, 3.657), stdev = 0.016
  CI (99.9%): [3.343, 3.935] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.976 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.772 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.656 ±(99.9%) 0.008 ms/op
Iteration   1: 4.525 ±(99.9%) 0.007 ms/op
Iteration   2: 4.545 ±(99.9%) 0.007 ms/op
Iteration   3: 4.515 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.528 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (4.515, 4.528, 4.545), stdev = 0.015
  CI (99.9%): [4.249, 4.807] (assumes normal distribution)


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
# Warmup Iteration   1: 5.241 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.008 ms/op
Iteration   1: 3.606 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.774 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  7.907 ms/op
                 createUser·p0.9999: 14.012 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 3.703 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   5.210 ms/op
                 createUser·p0.999:  8.510 ms/op
                 createUser·p0.9999: 19.138 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   3: 3.631 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.008 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.161 ms/op
                 createUser·p0.999:  11.862 ms/op
                 createUser·p0.9999: 19.896 ms/op
                 createUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 263398
  mean =      3.646 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5460 
    [ 2.500,  5.000) = 252842 
    [ 5.000,  7.500) = 4611 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.774 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      9.054 ms/op
     p(99.9900) =     18.950 ms/op
     p(99.9990) =     21.028 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.008 ms/op
Iteration   1: 3.433 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.202 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   4.891 ms/op
                 existUser·p0.999:  7.534 ms/op
                 existUser·p0.9999: 19.453 ms/op
                 existUser·p1.00:   20.087 ms/op

Iteration   2: 3.527 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   4.981 ms/op
                 existUser·p0.999:  6.185 ms/op
                 existUser·p0.9999: 18.411 ms/op
                 existUser·p1.00:   18.842 ms/op

Iteration   3: 3.517 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   4.825 ms/op
                 existUser·p0.999:  10.389 ms/op
                 existUser·p0.9999: 21.195 ms/op
                 existUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274914
  mean =      3.492 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14859 
    [ 2.500,  5.000) = 258091 
    [ 5.000,  7.500) = 1721 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      4.907 ms/op
     p(99.9000) =      7.300 ms/op
     p(99.9900) =     19.514 ms/op
     p(99.9990) =     21.471 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.070 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.760 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.007 ms/op
Iteration   1: 3.529 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.997 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  8.103 ms/op
                 getUser·p0.9999: 14.039 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   2: 3.584 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.887 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  8.664 ms/op
                 getUser·p0.9999: 16.848 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   3: 3.512 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  9.727 ms/op
                 getUser·p0.9999: 20.840 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 270860
  mean =      3.541 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9251 
    [ 2.500,  5.000) = 259024 
    [ 5.000,  7.500) = 2179 
    [ 7.500, 10.000) = 179 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      4.981 ms/op
     p(99.9000) =      8.555 ms/op
     p(99.9900) =     19.661 ms/op
     p(99.9990) =     21.062 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 5.617 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.895 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.611 ±(99.9%) 0.014 ms/op
Iteration   1: 4.526 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   4.383 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.308 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  15.701 ms/op
                 listUser·p0.9999: 21.852 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 4.475 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  15.550 ms/op
                 listUser·p0.9999: 18.663 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 4.492 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   4.325 ms/op
                 listUser·p0.90:   5.652 ms/op
                 listUser·p0.95:   6.283 ms/op
                 listUser·p0.99:   7.856 ms/op
                 listUser·p0.999:  19.352 ms/op
                 listUser·p0.9999: 24.105 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 213321
  mean =      4.498 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 626 
    [ 2.500,  5.000) = 178639 
    [ 5.000,  7.500) = 31262 
    [ 7.500, 10.000) = 2263 
    [10.000, 12.500) = 175 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      4.342 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.242 ms/op
     p(99.0000) =      7.758 ms/op
     p(99.9000) =     16.084 ms/op
     p(99.9900) =     22.337 ms/op
     p(99.9990) =     24.314 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.042 ± 2.754  ops/ms
ClientGrpc.existUser                       thrpt       3   9.265 ± 0.876  ops/ms
ClientGrpc.getUser                         thrpt       3   9.006 ± 4.439  ops/ms
ClientGrpc.listUser                        thrpt       3   7.170 ± 3.832  ops/ms
ClientGrpc.createUser                       avgt       3   3.754 ± 1.588   ms/op
ClientGrpc.existUser                        avgt       3   3.468 ± 0.987   ms/op
ClientGrpc.getUser                          avgt       3   3.639 ± 0.296   ms/op
ClientGrpc.listUser                         avgt       3   4.528 ± 0.279   ms/op
ClientGrpc.createUser                     sample  263398   3.646 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.774           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.267           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.054           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.950           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.135           ms/op
ClientGrpc.existUser                      sample  274914   3.492 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.554           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.293           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.907           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.300           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.514           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.529           ms/op
ClientGrpc.getUser                        sample  270860   3.541 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.772           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.527           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.555           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.661           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.660           ms/op
ClientGrpc.listUser                       sample  213321   4.498 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.860           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.342           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.084           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.337           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.445           ms/op
