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
# Warmup Iteration   1: 4.465 ops/ms
# Warmup Iteration   2: 8.879 ops/ms
# Warmup Iteration   3: 9.774 ops/ms
Iteration   1: 10.252 ops/ms
Iteration   2: 10.165 ops/ms
Iteration   3: 10.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.264 ±(99.9%) 1.909 ops/ms [Average]
  (min, avg, max) = (10.165, 10.264, 10.374), stdev = 0.105
  CI (99.9%): [8.354, 12.173] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.079 ops/ms
# Warmup Iteration   2: 10.439 ops/ms
# Warmup Iteration   3: 10.781 ops/ms
Iteration   1: 11.014 ops/ms
Iteration   2: 11.011 ops/ms
Iteration   3: 10.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.999 ±(99.9%) 0.440 ops/ms [Average]
  (min, avg, max) = (10.971, 10.999, 11.014), stdev = 0.024
  CI (99.9%): [10.558, 11.439] (assumes normal distribution)


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
# Warmup Iteration   1: 6.610 ops/ms
# Warmup Iteration   2: 9.860 ops/ms
# Warmup Iteration   3: 10.446 ops/ms
Iteration   1: 10.508 ops/ms
Iteration   2: 10.351 ops/ms
Iteration   3: 10.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.422 ±(99.9%) 1.457 ops/ms [Average]
  (min, avg, max) = (10.351, 10.422, 10.508), stdev = 0.080
  CI (99.9%): [8.965, 11.879] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.268 ops/ms
# Warmup Iteration   2: 7.352 ops/ms
# Warmup Iteration   3: 7.675 ops/ms
Iteration   1: 7.978 ops/ms
Iteration   2: 7.822 ops/ms
Iteration   3: 7.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.892 ±(99.9%) 1.445 ops/ms [Average]
  (min, avg, max) = (7.822, 7.892, 7.978), stdev = 0.079
  CI (99.9%): [6.448, 9.337] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.391 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.002 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
Iteration   3: 3.039 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.061 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (3.039, 3.061, 3.095), stdev = 0.030
  CI (99.9%): [2.521, 3.602] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.122 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.002 ms/op
Iteration   1: 2.991 ±(99.9%) 0.002 ms/op
Iteration   2: 2.908 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.968 ±(99.9%) 0.961 ms/op [Average]
  (min, avg, max) = (2.908, 2.968, 3.005), stdev = 0.053
  CI (99.9%): [2.007, 3.929] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.646 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.092 ±(99.9%) 0.003 ms/op
Iteration   1: 3.080 ±(99.9%) 0.002 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 3.090 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.069 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.036, 3.069, 3.090), stdev = 0.028
  CI (99.9%): [2.549, 3.589] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.880 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.218 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.015 ms/op
Iteration   1: 4.053 ±(99.9%) 0.020 ms/op
Iteration   2: 3.996 ±(99.9%) 0.011 ms/op
Iteration   3: 4.046 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.031 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.996, 4.031, 4.053), stdev = 0.031
  CI (99.9%): [3.461, 4.602] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.629 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
Iteration   1: 3.075 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.699 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  11.256 ms/op
                 createUser·p0.9999: 27.217 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   20.775 ms/op

Iteration   3: 3.054 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.925 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  8.695 ms/op
                 createUser·p0.9999: 19.170 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312142
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18377 
    [ 2.500,  5.000) = 291617 
    [ 5.000,  7.500) = 1449 
    [ 7.500, 10.000) = 381 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =     10.247 ms/op
     p(99.9900) =     20.148 ms/op
     p(99.9990) =     27.394 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 4.245 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 2.875 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.897 ms/op
                 existUser·p0.9999: 12.411 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   2: 2.942 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  7.898 ms/op
                 existUser·p0.9999: 14.373 ms/op
                 existUser·p1.00:   14.598 ms/op

Iteration   3: 2.913 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.583 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.500 ms/op
                 existUser·p0.9999: 17.008 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329815
  mean =      2.910 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3194 
    [ 1.250,  2.500) = 30381 
    [ 2.500,  3.750) = 285673 
    [ 3.750,  5.000) = 8979 
    [ 5.000,  6.250) = 635 
    [ 6.250,  7.500) = 545 
    [ 7.500,  8.750) = 177 
    [ 8.750, 10.000) = 63 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.774 ms/op
     p(99.9900) =     16.417 ms/op
     p(99.9990) =     17.249 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.251 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.009 ms/op
Iteration   1: 3.079 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  8.292 ms/op
                 getUser·p0.9999: 17.430 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   2: 3.118 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.888 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 19.521 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   3: 3.106 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.681 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 34.669 ms/op
                 getUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309501
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16583 
    [ 2.500,  5.000) = 290529 
    [ 5.000,  7.500) = 1694 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     32.930 ms/op
     p(99.9990) =     34.734 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


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
# Warmup Iteration   1: 5.322 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.242 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.011 ms/op
Iteration   1: 4.036 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.355 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.441 ms/op
                 listUser·p0.999:  14.265 ms/op
                 listUser·p0.9999: 17.603 ms/op
                 listUser·p1.00:   18.153 ms/op

Iteration   2: 4.020 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   6.029 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  14.729 ms/op
                 listUser·p0.9999: 23.532 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   3: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  17.688 ms/op
                 listUser·p0.9999: 19.338 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238107
  mean =      4.031 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2829 
    [ 2.500,  5.000) = 209665 
    [ 5.000,  7.500) = 23606 
    [ 7.500, 10.000) = 1525 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.355 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.324 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     22.006 ms/op
     p(99.9990) =     24.542 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.264 ± 1.909  ops/ms
ClientGrpc.existUser                       thrpt       3  10.999 ± 0.440  ops/ms
ClientGrpc.getUser                         thrpt       3  10.422 ± 1.457  ops/ms
ClientGrpc.listUser                        thrpt       3   7.892 ± 1.445  ops/ms
ClientGrpc.createUser                       avgt       3   3.061 ± 0.541   ms/op
ClientGrpc.existUser                        avgt       3   2.968 ± 0.961   ms/op
ClientGrpc.getUser                          avgt       3   3.069 ± 0.520   ms/op
ClientGrpc.listUser                         avgt       3   4.031 ± 0.571   ms/op
ClientGrpc.createUser                     sample  312142   3.076 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.699           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.580           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.247           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.148           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.460           ms/op
ClientGrpc.existUser                      sample  329815   2.910 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.583           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.774           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.417           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  309501   3.101 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.621           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.355           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.930           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.931           ms/op
ClientGrpc.listUser                       sample  238107   4.031 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.355           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.087           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.324           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.926           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.006           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.068           ms/op
