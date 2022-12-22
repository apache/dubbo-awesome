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
# Warmup Iteration   1: 4.876 ops/ms
# Warmup Iteration   2: 9.229 ops/ms
# Warmup Iteration   3: 10.207 ops/ms
Iteration   1: 10.127 ops/ms
Iteration   2: 10.226 ops/ms
Iteration   3: 10.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.155 ±(99.9%) 1.135 ops/ms [Average]
  (min, avg, max) = (10.112, 10.155, 10.226), stdev = 0.062
  CI (99.9%): [9.020, 11.289] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.962 ops/ms
# Warmup Iteration   2: 10.593 ops/ms
# Warmup Iteration   3: 10.905 ops/ms
Iteration   1: 10.845 ops/ms
Iteration   2: 11.368 ops/ms
Iteration   3: 10.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.059 ±(99.9%) 5.005 ops/ms [Average]
  (min, avg, max) = (10.845, 11.059, 11.368), stdev = 0.274
  CI (99.9%): [6.054, 16.064] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.920 ops/ms
# Warmup Iteration   2: 10.366 ops/ms
# Warmup Iteration   3: 10.383 ops/ms
Iteration   1: 10.633 ops/ms
Iteration   2: 10.542 ops/ms
Iteration   3: 10.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.540 ±(99.9%) 1.732 ops/ms [Average]
  (min, avg, max) = (10.443, 10.540, 10.633), stdev = 0.095
  CI (99.9%): [8.807, 12.272] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.458 ops/ms
# Warmup Iteration   2: 7.677 ops/ms
# Warmup Iteration   3: 7.740 ops/ms
Iteration   1: 7.974 ops/ms
Iteration   2: 8.073 ops/ms
Iteration   3: 7.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.985 ±(99.9%) 1.530 ops/ms [Average]
  (min, avg, max) = (7.906, 7.985, 8.073), stdev = 0.084
  CI (99.9%): [6.455, 9.515] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.002 ms/op
Iteration   1: 3.127 ±(99.9%) 0.002 ms/op
Iteration   2: 3.157 ±(99.9%) 0.002 ms/op
Iteration   3: 3.169 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.151 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (3.127, 3.151, 3.169), stdev = 0.021
  CI (99.9%): [2.761, 3.540] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 2.972 ±(99.9%) 0.002 ms/op
Iteration   2: 2.970 ±(99.9%) 0.002 ms/op
Iteration   3: 2.980 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 0.102 ms/op [Average]
  (min, avg, max) = (2.970, 2.974, 2.980), stdev = 0.006
  CI (99.9%): [2.872, 3.076] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.330 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.002 ms/op
Iteration   1: 3.040 ±(99.9%) 0.001 ms/op
Iteration   2: 3.058 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.029 ±(99.9%) 0.668 ms/op [Average]
  (min, avg, max) = (2.987, 3.029, 3.058), stdev = 0.037
  CI (99.9%): [2.360, 3.697] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.449 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.976 ±(99.9%) 0.033 ms/op
Iteration   1: 3.909 ±(99.9%) 0.016 ms/op
Iteration   2: 4.047 ±(99.9%) 0.032 ms/op
Iteration   3: 4.102 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.019 ±(99.9%) 1.808 ms/op [Average]
  (min, avg, max) = (3.909, 4.019, 4.102), stdev = 0.099
  CI (99.9%): [2.212, 5.827] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.906 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.190 ±(99.9%) 0.006 ms/op
Iteration   1: 3.132 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  7.616 ms/op
                 createUser·p0.9999: 13.461 ms/op
                 createUser·p1.00:   13.746 ms/op

Iteration   2: 3.154 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  9.537 ms/op
                 createUser·p0.9999: 14.230 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.382 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  11.834 ms/op
                 createUser·p0.9999: 23.535 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307385
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21518 
    [ 2.500,  5.000) = 284513 
    [ 5.000,  7.500) = 949 
    [ 7.500, 10.000) = 133 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.382 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     21.563 ms/op
     p(99.9990) =     23.817 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.951 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
Iteration   1: 2.870 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.039 ms/op
                 existUser·p0.9999: 14.725 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.529 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  5.816 ms/op
                 existUser·p0.9999: 12.604 ms/op
                 existUser·p1.00:   13.156 ms/op

Iteration   3: 2.972 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  7.692 ms/op
                 existUser·p0.9999: 14.352 ms/op
                 existUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326313
  mean =      2.940 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2212 
    [ 1.250,  2.500) = 46889 
    [ 2.500,  3.750) = 258907 
    [ 3.750,  5.000) = 17574 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 80 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 52 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.499 ms/op
     p(99.9900) =     14.467 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.909 ms/op
    p(100.0000) =     14.909 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.047 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.157 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
Iteration   1: 3.116 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.706 ms/op
                 getUser·p0.9999: 12.254 ms/op
                 getUser·p1.00:   12.698 ms/op

Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  6.373 ms/op
                 getUser·p0.9999: 21.155 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.247 ms/op
                 getUser·p0.9999: 25.061 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309061
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24142 
    [ 2.500,  5.000) = 283860 
    [ 5.000,  7.500) = 835 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.521 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     26.438 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.277 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.029 ±(99.9%) 0.012 ms/op
Iteration   1: 4.054 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  12.845 ms/op
                 listUser·p0.9999: 21.237 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   2: 3.992 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.331 ms/op
                 listUser·p0.9999: 22.117 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.776 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.980 ms/op
                 listUser·p0.9999: 22.596 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240624
  mean =      3.991 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4108 
    [ 2.500,  5.000) = 211065 
    [ 5.000,  7.500) = 24292 
    [ 7.500, 10.000) = 673 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 188 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     13.933 ms/op
     p(99.9900) =     22.249 ms/op
     p(99.9990) =     23.553 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.155 ± 1.135  ops/ms
ClientGrpc.existUser                       thrpt       3  11.059 ± 5.005  ops/ms
ClientGrpc.getUser                         thrpt       3  10.540 ± 1.732  ops/ms
ClientGrpc.listUser                        thrpt       3   7.985 ± 1.530  ops/ms
ClientGrpc.createUser                       avgt       3   3.151 ± 0.390   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 0.102   ms/op
ClientGrpc.getUser                          avgt       3   3.029 ± 0.668   ms/op
ClientGrpc.listUser                         avgt       3   4.019 ± 1.808   ms/op
ClientGrpc.createUser                     sample  307385   3.124 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.382           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.961           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.519           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.563           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.953           ms/op
ClientGrpc.existUser                      sample  326313   2.940 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.529           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.499           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.467           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          14.909           ms/op
ClientGrpc.getUser                        sample  309061   3.106 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.698           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.521           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.510           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.542           ms/op
ClientGrpc.listUser                       sample  240624   3.991 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.776           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.636           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.933           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.249           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.626           ms/op
