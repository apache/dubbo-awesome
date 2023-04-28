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
# Warmup Iteration   1: 4.347 ops/ms
# Warmup Iteration   2: 9.181 ops/ms
# Warmup Iteration   3: 10.188 ops/ms
Iteration   1: 10.691 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.642 ±(99.9%) 1.476 ops/ms [Average]
  (min, avg, max) = (10.549, 10.642, 10.691), stdev = 0.081
  CI (99.9%): [9.166, 12.119] (assumes normal distribution)


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
# Warmup Iteration   1: 8.140 ops/ms
# Warmup Iteration   2: 10.420 ops/ms
# Warmup Iteration   3: 11.172 ops/ms
Iteration   1: 11.244 ops/ms
Iteration   2: 10.416 ops/ms
Iteration   3: 10.795 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.818 ±(99.9%) 7.562 ops/ms [Average]
  (min, avg, max) = (10.416, 10.818, 11.244), stdev = 0.415
  CI (99.9%): [3.256, 18.380] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.441 ops/ms
# Warmup Iteration   2: 10.164 ops/ms
# Warmup Iteration   3: 10.468 ops/ms
Iteration   1: 10.497 ops/ms
Iteration   2: 10.472 ops/ms
Iteration   3: 10.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.508 ±(99.9%) 0.769 ops/ms [Average]
  (min, avg, max) = (10.472, 10.508, 10.554), stdev = 0.042
  CI (99.9%): [9.739, 11.276] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.975 ops/ms
# Warmup Iteration   2: 7.849 ops/ms
# Warmup Iteration   3: 8.125 ops/ms
Iteration   1: 8.253 ops/ms
Iteration   2: 8.188 ops/ms
Iteration   3: 8.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.178 ±(99.9%) 1.465 ops/ms [Average]
  (min, avg, max) = (8.093, 8.178, 8.253), stdev = 0.080
  CI (99.9%): [6.713, 9.643] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.309 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.002 ms/op
Iteration   1: 3.039 ±(99.9%) 0.003 ms/op
Iteration   2: 3.055 ±(99.9%) 0.002 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.046 ±(99.9%) 0.154 ms/op [Average]
  (min, avg, max) = (3.039, 3.046, 3.055), stdev = 0.008
  CI (99.9%): [2.892, 3.200] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.862 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.002 ms/op
Iteration   1: 2.948 ±(99.9%) 0.003 ms/op
Iteration   2: 2.829 ±(99.9%) 0.002 ms/op
Iteration   3: 2.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.896 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (2.829, 2.896, 2.948), stdev = 0.061
  CI (99.9%): [1.787, 4.004] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.258 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.122 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.002 ms/op
Iteration   1: 3.044 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
Iteration   3: 3.040 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.039 ms/op [Average]
  (min, avg, max) = (3.040, 3.043, 3.044), stdev = 0.002
  CI (99.9%): [3.004, 3.081] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.240 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.017 ms/op
Iteration   1: 3.912 ±(99.9%) 0.031 ms/op
Iteration   2: 3.842 ±(99.9%) 0.014 ms/op
Iteration   3: 3.895 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.883 ±(99.9%) 0.666 ms/op [Average]
  (min, avg, max) = (3.842, 3.883, 3.912), stdev = 0.037
  CI (99.9%): [3.217, 4.550] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.521 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.269 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
Iteration   1: 3.023 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.461 ms/op
                 createUser·p0.95:   3.604 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  6.928 ms/op
                 createUser·p0.9999: 12.154 ms/op
                 createUser·p1.00:   13.173 ms/op

Iteration   2: 3.045 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.739 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.137 ms/op
                 createUser·p0.999:  8.208 ms/op
                 createUser·p0.9999: 14.008 ms/op
                 createUser·p1.00:   14.238 ms/op

Iteration   3: 3.046 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  8.018 ms/op
                 createUser·p0.9999: 16.810 ms/op
                 createUser·p1.00:   16.843 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315927
  mean =      3.038 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 403 
    [ 1.250,  2.500) = 15860 
    [ 2.500,  3.750) = 286718 
    [ 3.750,  5.000) = 12046 
    [ 5.000,  6.250) = 267 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 130 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 41 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.874 ms/op
     p(99.9900) =     15.801 ms/op
     p(99.9990) =     16.843 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.901 ±(99.9%) 0.005 ms/op
Iteration   1: 2.910 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.856 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.291 ms/op
                 existUser·p0.9999: 18.415 ms/op
                 existUser·p1.00:   18.645 ms/op

Iteration   2: 2.889 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.211 ms/op
                 existUser·p0.95:   3.297 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  8.880 ms/op
                 existUser·p0.9999: 16.972 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   3: 2.846 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  6.062 ms/op
                 existUser·p0.9999: 14.377 ms/op
                 existUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333123
  mean =      2.881 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1283 
    [ 1.250,  2.500) = 35607 
    [ 2.500,  3.750) = 289116 
    [ 3.750,  5.000) = 6355 
    [ 5.000,  6.250) = 371 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.441 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =      6.463 ms/op
     p(99.9900) =     17.936 ms/op
     p(99.9990) =     18.569 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.078 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.711 ms/op
                 getUser·p0.9999: 12.318 ms/op
                 getUser·p1.00:   12.616 ms/op

Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.736 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.323 ms/op
                 getUser·p0.9999: 14.336 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   3: 3.063 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.591 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.739 ms/op
                 getUser·p0.9999: 16.648 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313651
  mean =      3.059 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 497 
    [ 1.250,  2.500) = 14218 
    [ 2.500,  3.750) = 282342 
    [ 3.750,  5.000) = 15453 
    [ 5.000,  6.250) = 561 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 138 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.591 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.807 ms/op
     p(99.9900) =     16.034 ms/op
     p(99.9990) =     16.937 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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
# Warmup Iteration   1: 4.938 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.010 ms/op
Iteration   1: 3.906 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  13.388 ms/op
                 listUser·p0.9999: 15.119 ms/op
                 listUser·p1.00:   15.598 ms/op

Iteration   2: 3.897 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  14.165 ms/op
                 listUser·p0.9999: 15.922 ms/op
                 listUser·p1.00:   16.450 ms/op

Iteration   3: 3.919 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 24.279 ms/op
                 listUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245856
  mean =      3.907 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2639 
    [ 2.500,  5.000) = 222916 
    [ 5.000,  7.500) = 19001 
    [ 7.500, 10.000) = 843 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.191 ms/op
     p(99.9900) =     22.604 ms/op
     p(99.9990) =     24.906 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.642 ± 1.476  ops/ms
ClientGrpc.existUser                       thrpt       3  10.818 ± 7.562  ops/ms
ClientGrpc.getUser                         thrpt       3  10.508 ± 0.769  ops/ms
ClientGrpc.listUser                        thrpt       3   8.178 ± 1.465  ops/ms
ClientGrpc.createUser                       avgt       3   3.046 ± 0.154   ms/op
ClientGrpc.existUser                        avgt       3   2.896 ± 1.109   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.039   ms/op
ClientGrpc.listUser                         avgt       3   3.883 ± 0.666   ms/op
ClientGrpc.createUser                     sample  315927   3.038 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.739           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.874           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.801           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.843           ms/op
ClientGrpc.existUser                      sample  333123   2.881 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.725           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.273           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.463           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.936           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.645           ms/op
ClientGrpc.getUser                        sample  313651   3.059 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.591           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.807           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.034           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.039           ms/op
ClientGrpc.listUser                       sample  245856   3.907 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.191           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.604           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.002           ms/op
