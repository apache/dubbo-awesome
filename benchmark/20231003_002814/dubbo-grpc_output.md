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
# Warmup Iteration   1: 4.039 ops/ms
# Warmup Iteration   2: 8.592 ops/ms
# Warmup Iteration   3: 9.453 ops/ms
Iteration   1: 9.927 ops/ms
Iteration   2: 9.960 ops/ms
Iteration   3: 10.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.106 ±(99.9%) 5.143 ops/ms [Average]
  (min, avg, max) = (9.927, 10.106, 10.431), stdev = 0.282
  CI (99.9%): [4.963, 15.249] (assumes normal distribution)


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
# Warmup Iteration   1: 7.087 ops/ms
# Warmup Iteration   2: 10.186 ops/ms
# Warmup Iteration   3: 11.060 ops/ms
Iteration   1: 10.603 ops/ms
Iteration   2: 10.963 ops/ms
Iteration   3: 11.020 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.862 ±(99.9%) 4.131 ops/ms [Average]
  (min, avg, max) = (10.603, 10.862, 11.020), stdev = 0.226
  CI (99.9%): [6.731, 14.992] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.490 ops/ms
# Warmup Iteration   2: 9.852 ops/ms
# Warmup Iteration   3: 10.243 ops/ms
Iteration   1: 10.238 ops/ms
Iteration   2: 10.243 ops/ms
Iteration   3: 10.304 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.262 ±(99.9%) 0.675 ops/ms [Average]
  (min, avg, max) = (10.238, 10.262, 10.304), stdev = 0.037
  CI (99.9%): [9.587, 10.937] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.204 ops/ms
# Warmup Iteration   2: 7.715 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 7.982 ops/ms
Iteration   2: 8.047 ops/ms
Iteration   3: 7.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.990 ±(99.9%) 0.968 ops/ms [Average]
  (min, avg, max) = (7.942, 7.990, 8.047), stdev = 0.053
  CI (99.9%): [7.023, 8.958] (assumes normal distribution)


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.143 ±(99.9%) 0.005 ms/op
Iteration   1: 3.203 ±(99.9%) 0.003 ms/op
Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
Iteration   3: 3.157 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.172 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.156, 3.172, 3.203), stdev = 0.027
  CI (99.9%): [2.685, 3.659] (assumes normal distribution)


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.003 ms/op
Iteration   1: 2.952 ±(99.9%) 0.003 ms/op
Iteration   2: 3.008 ±(99.9%) 0.005 ms/op
Iteration   3: 2.986 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.982 ±(99.9%) 0.516 ms/op [Average]
  (min, avg, max) = (2.952, 2.982, 3.008), stdev = 0.028
  CI (99.9%): [2.467, 3.498] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.278 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.002 ms/op
Iteration   1: 3.152 ±(99.9%) 0.004 ms/op
Iteration   2: 3.120 ±(99.9%) 0.004 ms/op
Iteration   3: 3.167 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.147 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (3.120, 3.147, 3.167), stdev = 0.024
  CI (99.9%): [2.708, 3.586] (assumes normal distribution)


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
# Warmup Iteration   1: 4.716 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.235 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.984 ±(99.9%) 0.015 ms/op
Iteration   1: 3.973 ±(99.9%) 0.039 ms/op
Iteration   2: 4.000 ±(99.9%) 0.022 ms/op
Iteration   3: 3.970 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.981 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.970, 3.981, 4.000), stdev = 0.016
  CI (99.9%): [3.680, 4.282] (assumes normal distribution)


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
# Warmup Iteration   1: 4.486 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.008 ms/op
Iteration   1: 3.132 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.882 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.846 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.421 ms/op
                 createUser·p0.9999: 19.457 ms/op
                 createUser·p1.00:   19.890 ms/op

Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  9.110 ms/op
                 createUser·p0.9999: 14.582 ms/op
                 createUser·p1.00:   15.155 ms/op

Iteration   3: 3.151 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.997 ms/op
                 createUser·p0.999:  16.410 ms/op
                 createUser·p0.9999: 24.931 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307340
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13007 
    [ 2.500,  5.000) = 292154 
    [ 5.000,  7.500) = 1566 
    [ 7.500, 10.000) = 234 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =     12.993 ms/op
     p(99.9900) =     22.848 ms/op
     p(99.9990) =     25.068 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 4.248 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  8.461 ms/op
                 existUser·p0.9999: 12.485 ms/op
                 existUser·p1.00:   15.630 ms/op

Iteration   2: 2.938 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.611 ms/op
                 existUser·p0.9999: 14.110 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 2.988 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.371 ms/op
                 existUser·p0.9999: 16.777 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321306
  mean =      2.988 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2233 
    [ 1.250,  2.500) = 27927 
    [ 2.500,  3.750) = 277789 
    [ 3.750,  5.000) = 11490 
    [ 5.000,  6.250) = 1114 
    [ 6.250,  7.500) = 382 
    [ 7.500,  8.750) = 138 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.473 ms/op
     p(99.9000) =      7.895 ms/op
     p(99.9900) =     16.183 ms/op
     p(99.9990) =     17.506 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.006 ms/op
Iteration   1: 3.146 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.720 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  10.207 ms/op
                 getUser·p0.9999: 17.787 ms/op
                 getUser·p1.00:   22.020 ms/op

Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.657 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 14.664 ms/op
                 getUser·p1.00:   16.646 ms/op

Iteration   3: 3.208 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.550 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.917 ms/op
                 getUser·p0.9999: 17.891 ms/op
                 getUser·p1.00:   18.317 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303626
  mean =      3.161 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9609 
    [ 2.500,  5.000) = 291955 
    [ 5.000,  7.500) = 1390 
    [ 7.500, 10.000) = 394 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     17.695 ms/op
     p(99.9990) =     18.315 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 5.840 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.011 ms/op
Iteration   1: 3.837 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.005 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.287 ms/op
                 listUser·p0.9999: 20.796 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 3.945 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.035 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.810 ms/op
                 listUser·p0.9999: 31.021 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   3: 3.947 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  15.608 ms/op
                 listUser·p0.9999: 18.084 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245573
  mean =      3.909 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2370 
    [ 2.500,  5.000) = 228528 
    [ 5.000,  7.500) = 13332 
    [ 7.500, 10.000) = 730 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.984 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     15.073 ms/op
     p(99.9900) =     26.383 ms/op
     p(99.9990) =     31.606 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.106 ± 5.143  ops/ms
ClientGrpc.existUser                       thrpt       3  10.862 ± 4.131  ops/ms
ClientGrpc.getUser                         thrpt       3  10.262 ± 0.675  ops/ms
ClientGrpc.listUser                        thrpt       3   7.990 ± 0.968  ops/ms
ClientGrpc.createUser                       avgt       3   3.172 ± 0.487   ms/op
ClientGrpc.existUser                        avgt       3   2.982 ± 0.516   ms/op
ClientGrpc.getUser                          avgt       3   3.147 ± 0.439   ms/op
ClientGrpc.listUser                         avgt       3   3.981 ± 0.301   ms/op
ClientGrpc.createUser                     sample  307340   3.126 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.744           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.993           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.848           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.231           ms/op
ClientGrpc.existUser                      sample  321306   2.988 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.650           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.473           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.895           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.183           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.383           ms/op
ClientGrpc.getUser                        sample  303626   3.161 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.550           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.694           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.650           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.695           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.020           ms/op
ClientGrpc.listUser                       sample  245573   3.909 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.984           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.251           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.865           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.073           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.383           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.621           ms/op
