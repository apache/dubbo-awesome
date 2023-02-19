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
# Warmup Iteration   1: 4.549 ops/ms
# Warmup Iteration   2: 9.330 ops/ms
# Warmup Iteration   3: 9.937 ops/ms
Iteration   1: 9.925 ops/ms
Iteration   2: 10.005 ops/ms
Iteration   3: 10.244 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.058 ±(99.9%) 3.027 ops/ms [Average]
  (min, avg, max) = (9.925, 10.058, 10.244), stdev = 0.166
  CI (99.9%): [7.030, 13.085] (assumes normal distribution)


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
# Warmup Iteration   1: 7.899 ops/ms
# Warmup Iteration   2: 10.069 ops/ms
# Warmup Iteration   3: 10.147 ops/ms
Iteration   1: 10.247 ops/ms
Iteration   2: 10.333 ops/ms
Iteration   3: 10.529 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.370 ±(99.9%) 2.629 ops/ms [Average]
  (min, avg, max) = (10.247, 10.370, 10.529), stdev = 0.144
  CI (99.9%): [7.740, 12.999] (assumes normal distribution)


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
# Warmup Iteration   1: 6.850 ops/ms
# Warmup Iteration   2: 9.648 ops/ms
# Warmup Iteration   3: 10.031 ops/ms
Iteration   1: 10.084 ops/ms
Iteration   2: 9.839 ops/ms
Iteration   3: 9.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.944 ±(99.9%) 2.303 ops/ms [Average]
  (min, avg, max) = (9.839, 9.944, 10.084), stdev = 0.126
  CI (99.9%): [7.640, 12.247] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.251 ops/ms
# Warmup Iteration   2: 7.365 ops/ms
# Warmup Iteration   3: 7.635 ops/ms
Iteration   1: 7.588 ops/ms
Iteration   2: 7.788 ops/ms
Iteration   3: 7.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.789 ±(99.9%) 3.678 ops/ms [Average]
  (min, avg, max) = (7.588, 7.789, 7.991), stdev = 0.202
  CI (99.9%): [4.111, 11.467] (assumes normal distribution)


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
# Warmup Iteration   1: 4.468 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.003 ms/op
Iteration   1: 3.278 ±(99.9%) 0.002 ms/op
Iteration   2: 3.251 ±(99.9%) 0.001 ms/op
Iteration   3: 3.136 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.221 ±(99.9%) 1.377 ms/op [Average]
  (min, avg, max) = (3.136, 3.221, 3.278), stdev = 0.075
  CI (99.9%): [1.844, 4.598] (assumes normal distribution)


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.088 ±(99.9%) 0.002 ms/op
Iteration   1: 3.048 ±(99.9%) 0.002 ms/op
Iteration   2: 2.977 ±(99.9%) 0.002 ms/op
Iteration   3: 2.990 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.005 ±(99.9%) 0.688 ms/op [Average]
  (min, avg, max) = (2.977, 3.005, 3.048), stdev = 0.038
  CI (99.9%): [2.317, 3.693] (assumes normal distribution)


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.002 ms/op
Iteration   1: 3.192 ±(99.9%) 0.006 ms/op
Iteration   2: 3.192 ±(99.9%) 0.002 ms/op
Iteration   3: 3.165 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.183 ±(99.9%) 0.280 ms/op [Average]
  (min, avg, max) = (3.165, 3.183, 3.192), stdev = 0.015
  CI (99.9%): [2.903, 3.464] (assumes normal distribution)


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
# Warmup Iteration   1: 5.294 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.323 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.120 ±(99.9%) 0.009 ms/op
Iteration   1: 4.110 ±(99.9%) 0.010 ms/op
Iteration   2: 4.078 ±(99.9%) 0.011 ms/op
Iteration   3: 3.874 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.021 ±(99.9%) 2.336 ms/op [Average]
  (min, avg, max) = (3.874, 4.021, 4.110), stdev = 0.128
  CI (99.9%): [1.684, 6.357] (assumes normal distribution)


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
# Warmup Iteration   1: 4.374 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.006 ms/op
Iteration   1: 3.177 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.006 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.987 ms/op
                 createUser·p0.9999: 20.344 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   2: 3.179 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.291 ms/op
                 createUser·p0.9999: 19.062 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   3: 3.165 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.174 ms/op
                 createUser·p0.9999: 21.365 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302298
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22079 
    [ 2.500,  5.000) = 279060 
    [ 5.000,  7.500) = 810 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.878 ms/op
     p(99.9900) =     21.022 ms/op
     p(99.9990) =     21.789 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 4.234 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.292 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.711 ms/op
                 existUser·p0.9999: 13.540 ms/op
                 existUser·p1.00:   13.844 ms/op

Iteration   2: 2.982 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.002 ms/op
                 existUser·p0.9999: 17.320 ms/op
                 existUser·p1.00:   17.793 ms/op

Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.781 ms/op
                 existUser·p0.50:   3.060 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.359 ms/op
                 existUser·p0.9999: 17.279 ms/op
                 existUser·p1.00:   17.793 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316389
  mean =      3.034 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1336 
    [ 1.250,  2.500) = 33788 
    [ 2.500,  3.750) = 259337 
    [ 3.750,  5.000) = 20836 
    [ 5.000,  6.250) = 483 
    [ 6.250,  7.500) = 295 
    [ 7.500,  8.750) = 120 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 75 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.292 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =     17.117 ms/op
     p(99.9990) =     17.788 ms/op
     p(99.9999) =     17.793 ms/op
    p(100.0000) =     17.793 ms/op


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
# Warmup Iteration   1: 4.427 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.006 ms/op
Iteration   1: 3.160 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.026 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  7.449 ms/op
                 getUser·p0.9999: 13.080 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   2: 3.211 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.985 ms/op
                 getUser·p0.50:   3.191 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.811 ms/op
                 getUser·p0.9999: 14.862 ms/op
                 getUser·p1.00:   15.254 ms/op

Iteration   3: 3.195 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.795 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  6.291 ms/op
                 getUser·p0.9999: 27.099 ms/op
                 getUser·p1.00:   27.394 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301016
  mean =      3.189 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21916 
    [ 2.500,  5.000) = 278172 
    [ 5.000,  7.500) = 691 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.143 ms/op
     p(99.9900) =     24.464 ms/op
     p(99.9990) =     27.296 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 5.411 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.011 ms/op
Iteration   1: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  13.128 ms/op
                 listUser·p0.9999: 16.273 ms/op
                 listUser·p1.00:   16.941 ms/op

Iteration   2: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  15.428 ms/op
                 listUser·p0.9999: 17.528 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   3: 4.136 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   3.936 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  23.265 ms/op
                 listUser·p0.9999: 26.288 ms/op
                 listUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236517
  mean =      4.060 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1708 
    [ 2.500,  5.000) = 208265 
    [ 5.000,  7.500) = 25216 
    [ 7.500, 10.000) = 857 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.442 ms/op
     p(99.9900) =     25.362 ms/op
     p(99.9990) =     26.473 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.058 ± 3.027  ops/ms
ClientGrpc.existUser                       thrpt       3  10.370 ± 2.629  ops/ms
ClientGrpc.getUser                         thrpt       3   9.944 ± 2.303  ops/ms
ClientGrpc.listUser                        thrpt       3   7.789 ± 3.678  ops/ms
ClientGrpc.createUser                       avgt       3   3.221 ± 1.377   ms/op
ClientGrpc.existUser                        avgt       3   3.005 ± 0.688   ms/op
ClientGrpc.getUser                          avgt       3   3.183 ± 0.280   ms/op
ClientGrpc.listUser                         avgt       3   4.021 ± 2.336   ms/op
ClientGrpc.createUser                     sample  302298   3.174 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.725           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.878           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.022           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.922           ms/op
ClientGrpc.existUser                      sample  316389   3.034 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.292           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.019           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.487           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.117           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.793           ms/op
ClientGrpc.getUser                        sample  301016   3.189 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.510           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.879           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.067           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.143           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.464           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.394           ms/op
ClientGrpc.listUser                       sample  236517   4.060 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.978           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.800           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.442           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.362           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.640           ms/op
