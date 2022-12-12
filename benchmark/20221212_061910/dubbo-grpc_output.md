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
# Warmup Iteration   1: 3.461 ops/ms
# Warmup Iteration   2: 7.786 ops/ms
# Warmup Iteration   3: 8.782 ops/ms
Iteration   1: 8.745 ops/ms
Iteration   2: 8.645 ops/ms
Iteration   3: 8.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.495 ±(99.9%) 6.379 ops/ms [Average]
  (min, avg, max) = (8.095, 8.495, 8.745), stdev = 0.350
  CI (99.9%): [2.116, 14.874] (assumes normal distribution)


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
# Warmup Iteration   1: 5.539 ops/ms
# Warmup Iteration   2: 7.762 ops/ms
# Warmup Iteration   3: 8.206 ops/ms
Iteration   1: 8.394 ops/ms
Iteration   2: 8.882 ops/ms
Iteration   3: 9.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.901 ±(99.9%) 9.418 ops/ms [Average]
  (min, avg, max) = (8.394, 8.901, 9.426), stdev = 0.516
  CI (99.9%): [≈ 0, 18.318] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.752 ops/ms
# Warmup Iteration   2: 8.561 ops/ms
# Warmup Iteration   3: 8.870 ops/ms
Iteration   1: 8.724 ops/ms
Iteration   2: 8.745 ops/ms
Iteration   3: 8.997 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.822 ±(99.9%) 2.767 ops/ms [Average]
  (min, avg, max) = (8.724, 8.822, 8.997), stdev = 0.152
  CI (99.9%): [6.055, 11.589] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.353 ops/ms
# Warmup Iteration   2: 6.405 ops/ms
# Warmup Iteration   3: 6.804 ops/ms
Iteration   1: 6.938 ops/ms
Iteration   2: 6.914 ops/ms
Iteration   3: 7.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.965 ±(99.9%) 1.270 ops/ms [Average]
  (min, avg, max) = (6.914, 6.965, 7.044), stdev = 0.070
  CI (99.9%): [5.695, 8.235] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.197 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.015 ms/op
Iteration   1: 3.620 ±(99.9%) 0.004 ms/op
Iteration   2: 3.583 ±(99.9%) 0.004 ms/op
Iteration   3: 3.725 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.643 ±(99.9%) 1.337 ms/op [Average]
  (min, avg, max) = (3.583, 3.643, 3.725), stdev = 0.073
  CI (99.9%): [2.306, 4.980] (assumes normal distribution)


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
# Warmup Iteration   1: 4.684 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.491 ±(99.9%) 0.003 ms/op
Iteration   1: 3.546 ±(99.9%) 0.003 ms/op
Iteration   2: 3.458 ±(99.9%) 0.003 ms/op
Iteration   3: 3.468 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.491 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (3.458, 3.491, 3.546), stdev = 0.048
  CI (99.9%): [2.612, 4.370] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.165 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.004 ms/op
Iteration   1: 3.648 ±(99.9%) 0.003 ms/op
Iteration   2: 3.603 ±(99.9%) 0.003 ms/op
Iteration   3: 3.595 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.615 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.595, 3.615, 3.648), stdev = 0.029
  CI (99.9%): [3.095, 4.135] (assumes normal distribution)


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
# Warmup Iteration   1: 5.841 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.787 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.017 ms/op
Iteration   1: 4.523 ±(99.9%) 0.026 ms/op
Iteration   2: 4.502 ±(99.9%) 0.015 ms/op
Iteration   3: 4.538 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.521 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (4.502, 4.521, 4.538), stdev = 0.018
  CI (99.9%): [4.186, 4.856] (assumes normal distribution)


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
# Warmup Iteration   1: 5.106 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.008 ms/op
Iteration   1: 3.568 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.535 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  12.113 ms/op
                 createUser·p0.9999: 15.041 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   2: 3.612 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.579 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  9.578 ms/op
                 createUser·p0.9999: 20.218 ms/op
                 createUser·p1.00:   20.447 ms/op

Iteration   3: 3.695 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.914 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  14.893 ms/op
                 createUser·p0.9999: 19.672 ms/op
                 createUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264847
  mean =      3.624 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8552 
    [ 2.500,  5.000) = 250979 
    [ 5.000,  7.500) = 4765 
    [ 7.500, 10.000) = 277 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     11.867 ms/op
     p(99.9900) =     20.038 ms/op
     p(99.9990) =     20.393 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 4.751 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.008 ms/op
Iteration   1: 3.511 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   4.825 ms/op
                 existUser·p0.999:  7.069 ms/op
                 existUser·p0.9999: 15.510 ms/op
                 existUser·p1.00:   15.827 ms/op

Iteration   2: 3.454 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.415 ms/op
                 existUser·p0.99:   4.833 ms/op
                 existUser·p0.999:  7.535 ms/op
                 existUser·p0.9999: 15.970 ms/op
                 existUser·p1.00:   16.237 ms/op

Iteration   3: 3.521 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.944 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  7.085 ms/op
                 existUser·p0.9999: 19.789 ms/op
                 existUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274496
  mean =      3.495 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9052 
    [ 2.500,  5.000) = 263374 
    [ 5.000,  7.500) = 1828 
    [ 7.500, 10.000) = 90 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.473 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =      7.299 ms/op
     p(99.9900) =     19.399 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.644 ms/op
    p(100.0000) =     20.644 ms/op


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
# Warmup Iteration   1: 5.093 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.749 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.008 ms/op
Iteration   1: 3.608 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.495 ms/op
                 getUser·p0.50:   3.584 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.300 ms/op
                 getUser·p0.999:  11.261 ms/op
                 getUser·p0.9999: 14.125 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 3.604 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.958 ms/op
                 getUser·p0.50:   3.576 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.071 ms/op
                 getUser·p0.999:  7.021 ms/op
                 getUser·p0.9999: 15.540 ms/op
                 getUser·p1.00:   16.007 ms/op

Iteration   3: 3.592 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.822 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.268 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.038 ms/op
                 getUser·p0.999:  15.548 ms/op
                 getUser·p0.9999: 18.224 ms/op
                 getUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 266658
  mean =      3.601 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 157 
    [ 1.250,  2.500) = 8622 
    [ 2.500,  3.750) = 156095 
    [ 3.750,  5.000) = 98185 
    [ 5.000,  6.250) = 2841 
    [ 6.250,  7.500) = 257 
    [ 7.500,  8.750) = 161 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 55 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 55 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     10.235 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     18.427 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 6.450 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.873 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.565 ±(99.9%) 0.013 ms/op
Iteration   1: 4.569 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.439 ms/op
                 listUser·p0.99:   7.889 ms/op
                 listUser·p0.999:  14.779 ms/op
                 listUser·p0.9999: 16.679 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   2: 4.613 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.751 ms/op
                 listUser·p0.95:   6.414 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  15.866 ms/op
                 listUser·p0.9999: 18.123 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 4.582 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.816 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   8.077 ms/op
                 listUser·p0.999:  18.494 ms/op
                 listUser·p0.9999: 25.593 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 209202
  mean =      4.588 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 440 
    [ 2.500,  5.000) = 168465 
    [ 5.000,  7.500) = 36559 
    [ 7.500, 10.000) = 3153 
    [10.000, 12.500) = 228 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      4.415 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.480 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     15.693 ms/op
     p(99.9900) =     23.956 ms/op
     p(99.9990) =     26.137 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.495 ± 6.379  ops/ms
ClientGrpc.existUser                       thrpt       3   8.901 ± 9.418  ops/ms
ClientGrpc.getUser                         thrpt       3   8.822 ± 2.767  ops/ms
ClientGrpc.listUser                        thrpt       3   6.965 ± 1.270  ops/ms
ClientGrpc.createUser                       avgt       3   3.643 ± 1.337   ms/op
ClientGrpc.existUser                        avgt       3   3.491 ± 0.879   ms/op
ClientGrpc.getUser                          avgt       3   3.615 ± 0.520   ms/op
ClientGrpc.listUser                         avgt       3   4.521 ± 0.335   ms/op
ClientGrpc.createUser                     sample  264847   3.624 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.801           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.686           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.267           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.867           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.038           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.447           ms/op
ClientGrpc.existUser                      sample  274496   3.495 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.907           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.473           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.899           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.299           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.399           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.644           ms/op
ClientGrpc.getUser                        sample  266658   3.601 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.495           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.596           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.128           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.235           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.859           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.514           ms/op
ClientGrpc.listUser                       sample  209202   4.588 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.333           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.415           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.480           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.693           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.956           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
