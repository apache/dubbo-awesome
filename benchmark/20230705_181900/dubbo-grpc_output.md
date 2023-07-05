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
# Warmup Iteration   1: 4.617 ops/ms
# Warmup Iteration   2: 9.318 ops/ms
# Warmup Iteration   3: 10.089 ops/ms
Iteration   1: 10.860 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.712 ±(99.9%) 2.386 ops/ms [Average]
  (min, avg, max) = (10.612, 10.712, 10.860), stdev = 0.131
  CI (99.9%): [8.326, 13.098] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.871 ops/ms
# Warmup Iteration   2: 10.873 ops/ms
# Warmup Iteration   3: 11.238 ops/ms
Iteration   1: 11.356 ops/ms
Iteration   2: 11.449 ops/ms
Iteration   3: 11.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.320 ±(99.9%) 2.739 ops/ms [Average]
  (min, avg, max) = (11.155, 11.320, 11.449), stdev = 0.150
  CI (99.9%): [8.581, 14.058] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.403 ops/ms
# Warmup Iteration   2: 10.554 ops/ms
# Warmup Iteration   3: 10.523 ops/ms
Iteration   1: 10.749 ops/ms
Iteration   2: 10.473 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.629 ±(99.9%) 2.572 ops/ms [Average]
  (min, avg, max) = (10.473, 10.629, 10.749), stdev = 0.141
  CI (99.9%): [8.056, 13.201] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.560 ops/ms
# Warmup Iteration   2: 8.057 ops/ms
# Warmup Iteration   3: 8.295 ops/ms
Iteration   1: 8.332 ops/ms
Iteration   2: 8.287 ops/ms
Iteration   3: 8.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.358 ±(99.9%) 1.584 ops/ms [Average]
  (min, avg, max) = (8.287, 8.358, 8.455), stdev = 0.087
  CI (99.9%): [6.774, 9.943] (assumes normal distribution)


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.002 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.017 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (3.009, 3.017, 3.031), stdev = 0.013
  CI (99.9%): [2.785, 3.249] (assumes normal distribution)


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
# Warmup Iteration   1: 3.873 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.864 ±(99.9%) 0.004 ms/op
Iteration   1: 2.878 ±(99.9%) 0.003 ms/op
Iteration   2: 2.878 ±(99.9%) 0.003 ms/op
Iteration   3: 2.851 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.869 ±(99.9%) 0.288 ms/op [Average]
  (min, avg, max) = (2.851, 2.869, 2.878), stdev = 0.016
  CI (99.9%): [2.581, 3.156] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.962 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.003 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
Iteration   3: 2.969 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.980 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (2.968, 2.980, 3.004), stdev = 0.020
  CI (99.9%): [2.609, 3.351] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.493 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.797 ±(99.9%) 0.005 ms/op
Iteration   1: 3.814 ±(99.9%) 0.018 ms/op
Iteration   2: 3.748 ±(99.9%) 0.017 ms/op
Iteration   3: 3.736 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.766 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (3.736, 3.766, 3.814), stdev = 0.042
  CI (99.9%): [2.997, 4.535] (assumes normal distribution)


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.007 ms/op
Iteration   1: 2.971 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.560 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.414 ms/op
                 createUser·p0.9999: 20.291 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  8.005 ms/op
                 createUser·p0.9999: 13.697 ms/op
                 createUser·p1.00:   13.861 ms/op

Iteration   3: 2.970 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.258 ms/op
                 createUser·p0.9999: 15.405 ms/op
                 createUser·p1.00:   15.778 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321679
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33465 
    [ 2.500,  5.000) = 286988 
    [ 5.000,  7.500) = 828 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.987 ms/op
     p(99.9900) =     18.050 ms/op
     p(99.9990) =     20.538 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.930 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
Iteration   1: 2.883 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.357 ms/op
                 existUser·p0.9999: 11.728 ms/op
                 existUser·p1.00:   12.599 ms/op

Iteration   2: 2.894 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  6.046 ms/op
                 existUser·p0.9999: 12.549 ms/op
                 existUser·p1.00:   12.747 ms/op

Iteration   3: 2.864 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  6.091 ms/op
                 existUser·p0.9999: 25.351 ms/op
                 existUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333173
  mean =      2.880 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44112 
    [ 2.500,  5.000) = 288288 
    [ 5.000,  7.500) = 578 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.226 ms/op
     p(99.9900) =     12.736 ms/op
     p(99.9990) =     25.581 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.793 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  6.856 ms/op
                 getUser·p0.9999: 11.676 ms/op
                 getUser·p1.00:   12.009 ms/op

Iteration   2: 2.955 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   2.970 ms/op
                 getUser·p0.90:   3.404 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.791 ms/op
                 getUser·p0.9999: 13.500 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   3: 2.956 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  6.787 ms/op
                 getUser·p0.9999: 17.367 ms/op
                 getUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323096
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1602 
    [ 1.250,  2.500) = 24472 
    [ 2.500,  3.750) = 285364 
    [ 3.750,  5.000) = 10594 
    [ 5.000,  6.250) = 583 
    [ 6.250,  7.500) = 203 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.807 ms/op
     p(99.9900) =     16.522 ms/op
     p(99.9990) =     17.992 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 4.281 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.011 ms/op
Iteration   1: 3.903 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.027 ms/op
                 listUser·p0.9999: 22.053 ms/op
                 listUser·p1.00:   22.315 ms/op

Iteration   2: 3.808 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.379 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  12.629 ms/op
                 listUser·p0.9999: 15.849 ms/op
                 listUser·p1.00:   16.679 ms/op

Iteration   3: 3.742 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.321 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 23.801 ms/op
                 listUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251506
  mean =      3.817 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4365 
    [ 2.500,  5.000) = 228425 
    [ 5.000,  7.500) = 17591 
    [ 7.500, 10.000) = 632 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.321 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.751 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.205 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     26.065 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.712 ± 2.386  ops/ms
ClientGrpc.existUser                       thrpt       3  11.320 ± 2.739  ops/ms
ClientGrpc.getUser                         thrpt       3  10.629 ± 2.572  ops/ms
ClientGrpc.listUser                        thrpt       3   8.358 ± 1.584  ops/ms
ClientGrpc.createUser                       avgt       3   3.017 ± 0.232   ms/op
ClientGrpc.existUser                        avgt       3   2.869 ± 0.288   ms/op
ClientGrpc.getUser                          avgt       3   2.980 ± 0.371   ms/op
ClientGrpc.listUser                         avgt       3   3.766 ± 0.769   ms/op
ClientGrpc.createUser                     sample  321679   2.983 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.560           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.987           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.050           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.578           ms/op
ClientGrpc.existUser                      sample  333173   2.880 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.226           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          12.736           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.657           ms/op
ClientGrpc.getUser                        sample  323096   2.970 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.740           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.650           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.807           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.522           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.448           ms/op
ClientGrpc.listUser                       sample  251506   3.817 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.321           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.751           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.390           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.205           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.184           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.182           ms/op
