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
# Warmup Iteration   1: 2.288 ops/ms
# Warmup Iteration   2: 5.665 ops/ms
# Warmup Iteration   3: 6.977 ops/ms
Iteration   1: 7.342 ops/ms
Iteration   2: 7.312 ops/ms
Iteration   3: 7.265 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.306 ±(99.9%) 0.701 ops/ms [Average]
  (min, avg, max) = (7.265, 7.306, 7.342), stdev = 0.038
  CI (99.9%): [6.605, 8.007] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.905 ops/ms
# Warmup Iteration   2: 7.413 ops/ms
# Warmup Iteration   3: 8.008 ops/ms
Iteration   1: 8.277 ops/ms
Iteration   2: 8.096 ops/ms
Iteration   3: 7.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.115 ±(99.9%) 2.782 ops/ms [Average]
  (min, avg, max) = (7.974, 8.115, 8.277), stdev = 0.152
  CI (99.9%): [5.334, 10.897] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.112 ops/ms
# Warmup Iteration   2: 6.612 ops/ms
# Warmup Iteration   3: 7.047 ops/ms
Iteration   1: 7.340 ops/ms
Iteration   2: 7.081 ops/ms
Iteration   3: 7.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.328 ±(99.9%) 4.405 ops/ms [Average]
  (min, avg, max) = (7.081, 7.328, 7.563), stdev = 0.241
  CI (99.9%): [2.923, 11.733] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ops/ms
# Warmup Iteration   2: 5.281 ops/ms
# Warmup Iteration   3: 5.674 ops/ms
Iteration   1: 5.648 ops/ms
Iteration   2: 5.724 ops/ms
Iteration   3: 5.760 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.711 ±(99.9%) 1.041 ops/ms [Average]
  (min, avg, max) = (5.648, 5.711, 5.760), stdev = 0.057
  CI (99.9%): [4.669, 6.752] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.557 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.496 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.306 ±(99.9%) 0.006 ms/op
Iteration   1: 4.377 ±(99.9%) 0.002 ms/op
Iteration   2: 4.321 ±(99.9%) 0.002 ms/op
Iteration   3: 4.229 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.309 ±(99.9%) 1.367 ms/op [Average]
  (min, avg, max) = (4.229, 4.309, 4.377), stdev = 0.075
  CI (99.9%): [2.942, 5.676] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.317 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.012 ms/op
Iteration   1: 4.119 ±(99.9%) 0.003 ms/op
Iteration   2: 4.103 ±(99.9%) 0.003 ms/op
Iteration   3: 4.081 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.101 ±(99.9%) 0.352 ms/op [Average]
  (min, avg, max) = (4.081, 4.101, 4.119), stdev = 0.019
  CI (99.9%): [3.748, 4.453] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.610 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.526 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.422 ±(99.9%) 0.004 ms/op
Iteration   1: 4.270 ±(99.9%) 0.002 ms/op
Iteration   2: 4.395 ±(99.9%) 0.003 ms/op
Iteration   3: 4.424 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.363 ±(99.9%) 1.488 ms/op [Average]
  (min, avg, max) = (4.270, 4.363, 4.424), stdev = 0.082
  CI (99.9%): [2.875, 5.851] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.090 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 5.668 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.501 ±(99.9%) 0.009 ms/op
Iteration   1: 5.333 ±(99.9%) 0.011 ms/op
Iteration   2: 5.413 ±(99.9%) 0.011 ms/op
Iteration   3: 5.437 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.394 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (5.333, 5.394, 5.437), stdev = 0.054
  CI (99.9%): [4.400, 6.388] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.380 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.689 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.559 ±(99.9%) 0.015 ms/op
Iteration   1: 4.306 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   4.178 ms/op
                 createUser·p0.90:   5.415 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.466 ms/op
                 createUser·p0.999:  14.483 ms/op
                 createUser·p0.9999: 22.582 ms/op
                 createUser·p1.00:   23.036 ms/op

Iteration   2: 4.343 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.325 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   7.274 ms/op
                 createUser·p0.999:  12.179 ms/op
                 createUser·p0.9999: 54.788 ms/op
                 createUser·p1.00:   55.378 ms/op

Iteration   3: 4.218 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.284 ms/op
                 createUser·p0.95:   5.784 ms/op
                 createUser·p0.99:   7.455 ms/op
                 createUser·p0.999:  10.653 ms/op
                 createUser·p0.9999: 24.603 ms/op
                 createUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 223703
  mean =      4.288 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 185405 
    [ 5.000, 10.000) = 37768 
    [10.000, 15.000) = 364 
    [15.000, 20.000) = 41 
    [20.000, 25.000) = 57 
    [25.000, 30.000) = 26 
    [30.000, 35.000) = 10 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      4.174 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.800 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     13.592 ms/op
     p(99.9900) =     53.621 ms/op
     p(99.9990) =     55.216 ms/op
     p(99.9999) =     55.378 ms/op
    p(100.0000) =     55.378 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.137 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.417 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.011 ms/op
Iteration   1: 4.101 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.128 ms/op
                 existUser·p0.95:   5.562 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  11.813 ms/op
                 existUser·p0.9999: 16.043 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 3.938 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   7.062 ms/op
                 existUser·p0.999:  12.317 ms/op
                 existUser·p0.9999: 25.142 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   3: 4.014 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   4.956 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.291 ms/op
                 existUser·p0.999:  11.671 ms/op
                 existUser·p0.9999: 33.000 ms/op
                 existUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238956
  mean =      4.017 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6171 
    [ 2.500,  5.000) = 208187 
    [ 5.000,  7.500) = 23313 
    [ 7.500, 10.000) = 958 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     31.461 ms/op
     p(99.9990) =     33.300 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.776 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.628 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.443 ±(99.9%) 0.012 ms/op
Iteration   1: 4.359 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.895 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   6.062 ms/op
                 getUser·p0.99:   7.987 ms/op
                 getUser·p0.999:  12.124 ms/op
                 getUser·p0.9999: 16.575 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   2: 4.320 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   5.923 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  10.994 ms/op
                 getUser·p0.9999: 16.630 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 4.509 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  10.732 ms/op
                 getUser·p0.9999: 18.874 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 218324
  mean =      4.394 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3062 
    [ 2.500,  5.000) = 170081 
    [ 5.000,  7.500) = 43099 
    [ 7.500, 10.000) = 1598 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      4.276 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     11.813 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     21.373 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.361 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 5.939 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.668 ±(99.9%) 0.023 ms/op
Iteration   1: 5.668 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   7.815 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.616 ms/op
                 listUser·p0.999:  18.630 ms/op
                 listUser·p0.9999: 20.583 ms/op
                 listUser·p1.00:   21.070 ms/op

Iteration   2: 5.670 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.587 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   7.946 ms/op
                 listUser·p0.95:   8.864 ms/op
                 listUser·p0.99:   11.010 ms/op
                 listUser·p0.999:  16.877 ms/op
                 listUser·p0.9999: 24.862 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   3: 5.827 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   5.464 ms/op
                 listUser·p0.90:   8.020 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   10.912 ms/op
                 listUser·p0.999:  26.247 ms/op
                 listUser·p0.9999: 35.554 ms/op
                 listUser·p1.00:   36.372 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 167734
  mean =      5.721 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 294 
    [ 2.500,  5.000) = 63099 
    [ 5.000,  7.500) = 82103 
    [ 7.500, 10.000) = 18637 
    [10.000, 12.500) = 2727 
    [12.500, 15.000) = 520 
    [15.000, 17.500) = 117 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      7.930 ms/op
     p(95.0000) =      8.880 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     19.506 ms/op
     p(99.9900) =     33.768 ms/op
     p(99.9990) =     36.195 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.306 ± 0.701  ops/ms
ClientGrpc.existUser                       thrpt       3   8.115 ± 2.782  ops/ms
ClientGrpc.getUser                         thrpt       3   7.328 ± 4.405  ops/ms
ClientGrpc.listUser                        thrpt       3   5.711 ± 1.041  ops/ms
ClientGrpc.createUser                       avgt       3   4.309 ± 1.367   ms/op
ClientGrpc.existUser                        avgt       3   4.101 ± 0.352   ms/op
ClientGrpc.getUser                          avgt       3   4.363 ± 1.488   ms/op
ClientGrpc.listUser                         avgt       3   5.394 ± 0.994   ms/op
ClientGrpc.createUser                     sample  223703   4.288 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.915           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.174           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.341           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.800           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.406           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.592           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          53.621           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          55.378           ms/op
ClientGrpc.existUser                      sample  238956   4.017 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.059           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.014           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.448           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.726           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.813           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.461           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.423           ms/op
ClientGrpc.getUser                        sample  218324   4.394 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.895           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.980           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.447           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.813           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.317           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  167734   5.721 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.178           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.930           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.880           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.141           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.506           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.768           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          36.372           ms/op
