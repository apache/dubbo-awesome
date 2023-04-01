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
# Warmup Iteration   1: 3.322 ops/ms
# Warmup Iteration   2: 7.011 ops/ms
# Warmup Iteration   3: 8.777 ops/ms
Iteration   1: 9.519 ops/ms
Iteration   2: 9.626 ops/ms
Iteration   3: 9.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.577 ±(99.9%) 0.993 ops/ms [Average]
  (min, avg, max) = (9.519, 9.577, 9.626), stdev = 0.054
  CI (99.9%): [8.584, 10.570] (assumes normal distribution)


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
# Warmup Iteration   1: 6.425 ops/ms
# Warmup Iteration   2: 9.417 ops/ms
# Warmup Iteration   3: 9.718 ops/ms
Iteration   1: 9.608 ops/ms
Iteration   2: 9.776 ops/ms
Iteration   3: 9.823 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.736 ±(99.9%) 2.062 ops/ms [Average]
  (min, avg, max) = (9.608, 9.736, 9.823), stdev = 0.113
  CI (99.9%): [7.673, 11.798] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.926 ops/ms
# Warmup Iteration   2: 8.950 ops/ms
# Warmup Iteration   3: 9.383 ops/ms
Iteration   1: 9.106 ops/ms
Iteration   2: 9.215 ops/ms
Iteration   3: 9.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.154 ±(99.9%) 1.018 ops/ms [Average]
  (min, avg, max) = (9.106, 9.154, 9.215), stdev = 0.056
  CI (99.9%): [8.136, 10.172] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.554 ops/ms
# Warmup Iteration   2: 6.710 ops/ms
# Warmup Iteration   3: 6.934 ops/ms
Iteration   1: 7.217 ops/ms
Iteration   2: 7.046 ops/ms
Iteration   3: 7.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.115 ±(99.9%) 1.642 ops/ms [Average]
  (min, avg, max) = (7.046, 7.115, 7.217), stdev = 0.090
  CI (99.9%): [5.474, 8.757] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.629 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.369 ±(99.9%) 0.003 ms/op
Iteration   1: 3.363 ±(99.9%) 0.003 ms/op
Iteration   2: 3.525 ±(99.9%) 0.003 ms/op
Iteration   3: 3.449 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.446 ±(99.9%) 1.480 ms/op [Average]
  (min, avg, max) = (3.363, 3.446, 3.525), stdev = 0.081
  CI (99.9%): [1.966, 4.926] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.332 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.368 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.253 ±(99.9%) 0.003 ms/op
Iteration   1: 3.250 ±(99.9%) 0.003 ms/op
Iteration   2: 3.291 ±(99.9%) 0.003 ms/op
Iteration   3: 3.227 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.256 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (3.227, 3.256, 3.291), stdev = 0.033
  CI (99.9%): [2.660, 3.852] (assumes normal distribution)


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
# Warmup Iteration   1: 5.239 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.003 ms/op
Iteration   1: 3.449 ±(99.9%) 0.004 ms/op
Iteration   2: 3.380 ±(99.9%) 0.005 ms/op
Iteration   3: 3.445 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.425 ±(99.9%) 0.705 ms/op [Average]
  (min, avg, max) = (3.380, 3.425, 3.449), stdev = 0.039
  CI (99.9%): [2.719, 4.130] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.591 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.762 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.532 ±(99.9%) 0.011 ms/op
Iteration   1: 4.573 ±(99.9%) 0.029 ms/op
Iteration   2: 4.551 ±(99.9%) 0.013 ms/op
Iteration   3: 4.443 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.523 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (4.443, 4.523, 4.573), stdev = 0.069
  CI (99.9%): [3.257, 5.788] (assumes normal distribution)


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
# Warmup Iteration   1: 5.051 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.431 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.350 ±(99.9%) 0.008 ms/op
Iteration   1: 3.281 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.145 ms/op
                 createUser·p0.999:  8.423 ms/op
                 createUser·p0.9999: 13.902 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 3.258 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.794 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.899 ms/op
                 createUser·p0.999:  14.664 ms/op
                 createUser·p0.9999: 17.078 ms/op
                 createUser·p1.00:   17.924 ms/op

Iteration   3: 3.261 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.340 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.941 ms/op
                 createUser·p0.999:  9.107 ms/op
                 createUser·p0.9999: 17.727 ms/op
                 createUser·p1.00:   20.087 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 293885
  mean =      3.267 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17209 
    [ 2.500,  5.000) = 273694 
    [ 5.000,  7.500) = 2493 
    [ 7.500, 10.000) = 188 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.340 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      5.014 ms/op
     p(99.9000) =     10.174 ms/op
     p(99.9900) =     17.531 ms/op
     p(99.9990) =     18.864 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.459 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.007 ms/op
Iteration   1: 3.289 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  7.737 ms/op
                 existUser·p0.9999: 22.014 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.191 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.356 ms/op
                 existUser·p0.9999: 17.531 ms/op
                 existUser·p1.00:   19.169 ms/op

Iteration   3: 3.241 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   4.628 ms/op
                 existUser·p0.999:  7.242 ms/op
                 existUser·p0.9999: 18.490 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 296233
  mean =      3.240 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10347 
    [ 2.500,  5.000) = 284491 
    [ 5.000,  7.500) = 1116 
    [ 7.500, 10.000) = 81 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.497 ms/op
     p(99.9000) =      7.315 ms/op
     p(99.9900) =     20.890 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.686 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.365 ±(99.9%) 0.008 ms/op
Iteration   1: 3.410 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  11.704 ms/op
                 getUser·p0.9999: 15.251 ms/op
                 getUser·p1.00:   16.073 ms/op

Iteration   2: 3.351 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   4.940 ms/op
                 getUser·p0.999:  6.672 ms/op
                 getUser·p0.9999: 16.237 ms/op
                 getUser·p1.00:   16.613 ms/op

Iteration   3: 3.369 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.923 ms/op
                 getUser·p0.999:  9.717 ms/op
                 getUser·p0.9999: 19.469 ms/op
                 getUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 284300
  mean =      3.376 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9666 
    [ 2.500,  5.000) = 271530 
    [ 5.000,  7.500) = 2624 
    [ 7.500, 10.000) = 263 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.095 ms/op
     p(99.9000) =      9.034 ms/op
     p(99.9900) =     18.041 ms/op
     p(99.9990) =     20.551 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 6.280 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.636 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.394 ±(99.9%) 0.012 ms/op
Iteration   1: 4.360 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.087 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  15.519 ms/op
                 listUser·p0.9999: 21.506 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   2: 4.352 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   4.190 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.423 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 21.633 ms/op
                 listUser·p1.00:   22.053 ms/op

Iteration   3: 4.450 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   4.309 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.218 ms/op
                 listUser·p0.99:   7.709 ms/op
                 listUser·p0.999:  17.826 ms/op
                 listUser·p0.9999: 20.527 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 218959
  mean =      4.387 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1072 
    [ 2.500,  5.000) = 187585 
    [ 5.000,  7.500) = 27787 
    [ 7.500, 10.000) = 2020 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      6.234 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     15.909 ms/op
     p(99.9900) =     21.372 ms/op
     p(99.9990) =     21.981 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.577 ± 0.993  ops/ms
ClientGrpc.existUser                       thrpt       3   9.736 ± 2.062  ops/ms
ClientGrpc.getUser                         thrpt       3   9.154 ± 1.018  ops/ms
ClientGrpc.listUser                        thrpt       3   7.115 ± 1.642  ops/ms
ClientGrpc.createUser                       avgt       3   3.446 ± 1.480   ms/op
ClientGrpc.existUser                        avgt       3   3.256 ± 0.596   ms/op
ClientGrpc.getUser                          avgt       3   3.425 ± 0.705   ms/op
ClientGrpc.listUser                         avgt       3   4.523 ± 1.265   ms/op
ClientGrpc.createUser                     sample  293885   3.267 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.340           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.248           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.088           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.174           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.531           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.087           ms/op
ClientGrpc.existUser                      sample  296233   3.240 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.724           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.232           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.895           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.497           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.315           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.890           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.019           ms/op
ClientGrpc.getUser                        sample  284300   3.376 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.588           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.351           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.936           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.095           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.034           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.041           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.578           ms/op
ClientGrpc.listUser                       sample  218959   4.387 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.122           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.235           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.234           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.619           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.909           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.372           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.053           ms/op
