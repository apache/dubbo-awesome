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
# Warmup Iteration   1: 4.974 ops/ms
# Warmup Iteration   2: 10.068 ops/ms
# Warmup Iteration   3: 10.551 ops/ms
Iteration   1: 10.749 ops/ms
Iteration   2: 10.484 ops/ms
Iteration   3: 10.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.546 ±(99.9%) 3.279 ops/ms [Average]
  (min, avg, max) = (10.406, 10.546, 10.749), stdev = 0.180
  CI (99.9%): [7.268, 13.825] (assumes normal distribution)


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
# Warmup Iteration   1: 9.049 ops/ms
# Warmup Iteration   2: 10.627 ops/ms
# Warmup Iteration   3: 10.868 ops/ms
Iteration   1: 11.094 ops/ms
Iteration   2: 11.087 ops/ms
Iteration   3: 11.055 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.078 ±(99.9%) 0.378 ops/ms [Average]
  (min, avg, max) = (11.055, 11.078, 11.094), stdev = 0.021
  CI (99.9%): [10.701, 11.456] (assumes normal distribution)


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
# Warmup Iteration   1: 7.558 ops/ms
# Warmup Iteration   2: 10.422 ops/ms
# Warmup Iteration   3: 10.537 ops/ms
Iteration   1: 10.577 ops/ms
Iteration   2: 10.592 ops/ms
Iteration   3: 10.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.592 ±(99.9%) 0.281 ops/ms [Average]
  (min, avg, max) = (10.577, 10.592, 10.608), stdev = 0.015
  CI (99.9%): [10.312, 10.873] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.256 ops/ms
# Warmup Iteration   2: 7.988 ops/ms
# Warmup Iteration   3: 7.810 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 8.097 ops/ms
Iteration   3: 8.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.168 ±(99.9%) 4.549 ops/ms [Average]
  (min, avg, max) = (7.963, 8.168, 8.446), stdev = 0.249
  CI (99.9%): [3.619, 12.718] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.693 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.003 ms/op
Iteration   1: 2.974 ±(99.9%) 0.003 ms/op
Iteration   2: 3.076 ±(99.9%) 0.002 ms/op
Iteration   3: 2.998 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.016 ±(99.9%) 0.975 ms/op [Average]
  (min, avg, max) = (2.974, 3.016, 3.076), stdev = 0.053
  CI (99.9%): [2.041, 3.991] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.545 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.004 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 2.847 ±(99.9%) 0.004 ms/op
Iteration   2: 2.837 ±(99.9%) 0.004 ms/op
Iteration   3: 2.947 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.877 ±(99.9%) 1.101 ms/op [Average]
  (min, avg, max) = (2.837, 2.877, 2.947), stdev = 0.060
  CI (99.9%): [1.776, 3.978] (assumes normal distribution)


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
# Warmup Iteration   1: 3.629 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.003 ms/op
Iteration   1: 2.988 ±(99.9%) 0.002 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.007 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (2.988, 3.007, 3.020), stdev = 0.017
  CI (99.9%): [2.703, 3.310] (assumes normal distribution)


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
# Warmup Iteration   1: 4.510 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.030 ms/op
Iteration   1: 3.884 ±(99.9%) 0.048 ms/op
Iteration   2: 3.887 ±(99.9%) 0.028 ms/op
Iteration   3: 3.928 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.900 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (3.884, 3.900, 3.928), stdev = 0.025
  CI (99.9%): [3.451, 4.348] (assumes normal distribution)


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  6.074 ms/op
                 createUser·p0.9999: 11.365 ms/op
                 createUser·p1.00:   11.616 ms/op

Iteration   2: 2.970 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.200 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  8.489 ms/op
                 createUser·p0.9999: 22.224 ms/op
                 createUser·p1.00:   22.643 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  11.731 ms/op
                 createUser·p0.9999: 17.826 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315179
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33889 
    [ 2.500,  5.000) = 280514 
    [ 5.000,  7.500) = 385 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.200 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      9.486 ms/op
     p(99.9900) =     21.660 ms/op
     p(99.9990) =     22.567 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 3.727 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.886 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.006 ms/op
Iteration   1: 2.899 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.117 ms/op
                 existUser·p0.9999: 16.138 ms/op
                 existUser·p1.00:   16.499 ms/op

Iteration   2: 2.901 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.888 ms/op
                 existUser·p0.9999: 15.925 ms/op
                 existUser·p1.00:   16.286 ms/op

Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.653 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  8.767 ms/op
                 existUser·p0.9999: 16.024 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327003
  mean =      2.934 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3658 
    [ 1.250,  2.500) = 51066 
    [ 2.500,  3.750) = 254002 
    [ 3.750,  5.000) = 17531 
    [ 5.000,  6.250) = 363 
    [ 6.250,  7.500) = 124 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 99 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.133 ms/op
     p(99.9000) =      6.545 ms/op
     p(99.9900) =     16.024 ms/op
     p(99.9990) =     17.209 ms/op
     p(99.9999) =     17.498 ms/op
    p(100.0000) =     17.498 ms/op


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
# Warmup Iteration   1: 3.660 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.005 ms/op
Iteration   1: 3.008 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.498 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  5.321 ms/op
                 getUser·p0.9999: 12.070 ms/op
                 getUser·p1.00:   12.370 ms/op

Iteration   2: 2.933 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.987 ms/op
                 getUser·p0.9999: 12.535 ms/op
                 getUser·p1.00:   13.648 ms/op

Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  8.017 ms/op
                 getUser·p0.9999: 17.828 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320188
  mean =      2.998 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1559 
    [ 1.250,  2.500) = 35627 
    [ 2.500,  3.750) = 263346 
    [ 3.750,  5.000) = 18789 
    [ 5.000,  6.250) = 455 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.498 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.804 ms/op
     p(99.9900) =     16.471 ms/op
     p(99.9990) =     18.049 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.670 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.173 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.012 ms/op
Iteration   1: 3.989 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.293 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.429 ms/op
                 listUser·p0.9999: 18.939 ms/op
                 listUser·p1.00:   19.300 ms/op

Iteration   2: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  13.717 ms/op
                 listUser·p0.9999: 17.893 ms/op
                 listUser·p1.00:   18.383 ms/op

Iteration   3: 3.939 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.869 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  17.291 ms/op
                 listUser·p0.9999: 21.689 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240645
  mean =      3.985 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3180 
    [ 2.500,  5.000) = 209491 
    [ 5.000,  7.500) = 26769 
    [ 7.500, 10.000) = 707 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.293 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     14.506 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     26.429 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.546 ± 3.279  ops/ms
ClientGrpc.existUser                       thrpt       3  11.078 ± 0.378  ops/ms
ClientGrpc.getUser                         thrpt       3  10.592 ± 0.281  ops/ms
ClientGrpc.listUser                        thrpt       3   8.168 ± 4.549  ops/ms
ClientGrpc.createUser                       avgt       3   3.016 ± 0.975   ms/op
ClientGrpc.existUser                        avgt       3   2.877 ± 1.101   ms/op
ClientGrpc.getUser                          avgt       3   3.007 ± 0.303   ms/op
ClientGrpc.listUser                         avgt       3   3.900 ± 0.448   ms/op
ClientGrpc.createUser                     sample  315179   3.046 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.200           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.202           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.486           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.660           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.643           ms/op
ClientGrpc.existUser                      sample  327003   2.934 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.568           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.133           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.545           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.024           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.498           ms/op
ClientGrpc.getUser                        sample  320188   2.998 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.498           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.804           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.471           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  240645   3.985 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.293           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.506           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.299           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.575           ms/op
