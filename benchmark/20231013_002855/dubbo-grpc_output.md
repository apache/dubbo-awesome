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
# Warmup Iteration   1: 4.607 ops/ms
# Warmup Iteration   2: 9.214 ops/ms
# Warmup Iteration   3: 9.828 ops/ms
Iteration   1: 10.062 ops/ms
Iteration   2: 10.248 ops/ms
Iteration   3: 10.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.197 ±(99.9%) 2.172 ops/ms [Average]
  (min, avg, max) = (10.062, 10.197, 10.283), stdev = 0.119
  CI (99.9%): [8.026, 12.369] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.148 ops/ms
# Warmup Iteration   2: 10.479 ops/ms
# Warmup Iteration   3: 10.805 ops/ms
Iteration   1: 10.718 ops/ms
Iteration   2: 10.687 ops/ms
Iteration   3: 10.849 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.751 ±(99.9%) 1.571 ops/ms [Average]
  (min, avg, max) = (10.687, 10.751, 10.849), stdev = 0.086
  CI (99.9%): [9.180, 12.323] (assumes normal distribution)


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
# Warmup Iteration   1: 7.164 ops/ms
# Warmup Iteration   2: 9.560 ops/ms
# Warmup Iteration   3: 10.241 ops/ms
Iteration   1: 10.475 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.457 ±(99.9%) 1.979 ops/ms [Average]
  (min, avg, max) = (10.341, 10.457, 10.556), stdev = 0.108
  CI (99.9%): [8.478, 12.436] (assumes normal distribution)


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
# Warmup Iteration   1: 5.736 ops/ms
# Warmup Iteration   2: 7.657 ops/ms
# Warmup Iteration   3: 7.958 ops/ms
Iteration   1: 7.866 ops/ms
Iteration   2: 7.883 ops/ms
Iteration   3: 8.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.928 ±(99.9%) 1.686 ops/ms [Average]
  (min, avg, max) = (7.866, 7.928, 8.034), stdev = 0.092
  CI (99.9%): [6.242, 9.614] (assumes normal distribution)


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
# Warmup Iteration   1: 4.577 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 3.027 ±(99.9%) 0.004 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.050 ±(99.9%) 0.717 ms/op [Average]
  (min, avg, max) = (3.027, 3.050, 3.096), stdev = 0.039
  CI (99.9%): [2.333, 3.767] (assumes normal distribution)


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
# Warmup Iteration   1: 4.180 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.003 ms/op
Iteration   1: 3.020 ±(99.9%) 0.003 ms/op
Iteration   2: 2.956 ±(99.9%) 0.003 ms/op
Iteration   3: 3.030 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.002 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (2.956, 3.002, 3.030), stdev = 0.040
  CI (99.9%): [2.272, 3.732] (assumes normal distribution)


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
# Warmup Iteration   1: 4.558 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.002 ms/op
Iteration   2: 3.156 ±(99.9%) 0.002 ms/op
Iteration   3: 3.144 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.118 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (3.055, 3.118, 3.156), stdev = 0.055
  CI (99.9%): [2.117, 4.120] (assumes normal distribution)


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
# Warmup Iteration   1: 5.675 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.141 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.029 ms/op
Iteration   1: 3.912 ±(99.9%) 0.014 ms/op
Iteration   2: 3.980 ±(99.9%) 0.016 ms/op
Iteration   3: 3.945 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.946 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (3.912, 3.946, 3.980), stdev = 0.034
  CI (99.9%): [3.325, 4.566] (assumes normal distribution)


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
Iteration   1: 3.161 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.795 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  8.877 ms/op
                 createUser·p0.9999: 16.286 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   2: 3.148 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.564 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  8.383 ms/op
                 createUser·p0.9999: 19.131 ms/op
                 createUser·p1.00:   19.497 ms/op

Iteration   3: 3.099 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   5.014 ms/op
                 createUser·p0.999:  11.139 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305974
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13997 
    [ 2.500,  5.000) = 288551 
    [ 5.000,  7.500) = 2803 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.112 ms/op
     p(99.9000) =      8.979 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     25.166 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 3.795 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.667 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.694 ms/op
                 existUser·p0.999:  7.242 ms/op
                 existUser·p0.9999: 17.312 ms/op
                 existUser·p1.00:   17.727 ms/op

Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  9.788 ms/op
                 existUser·p0.9999: 14.781 ms/op
                 existUser·p1.00:   15.122 ms/op

Iteration   3: 3.059 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.713 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  12.501 ms/op
                 existUser·p0.9999: 17.665 ms/op
                 existUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 317602
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1478 
    [ 1.250,  2.500) = 22493 
    [ 2.500,  3.750) = 276059 
    [ 3.750,  5.000) = 14831 
    [ 5.000,  6.250) = 1509 
    [ 6.250,  7.500) = 702 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 40 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 71 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.667 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.858 ms/op
     p(99.9000) =      8.723 ms/op
     p(99.9900) =     17.367 ms/op
     p(99.9990) =     18.911 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.537 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.151 ±(99.9%) 0.007 ms/op
Iteration   1: 3.074 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.700 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.833 ms/op
                 getUser·p0.999:  7.184 ms/op
                 getUser·p0.9999: 17.812 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  7.129 ms/op
                 getUser·p0.9999: 19.005 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   3: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.578 ms/op
                 getUser·p0.9999: 19.071 ms/op
                 getUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311271
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 465 
    [ 1.250,  2.500) = 14368 
    [ 2.500,  3.750) = 276858 
    [ 3.750,  5.000) = 17446 
    [ 5.000,  6.250) = 1438 
    [ 6.250,  7.500) = 437 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 38 
    [17.500, 18.750) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =      7.184 ms/op
     p(99.9900) =     18.940 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.890 ms/op
    p(100.0000) =     19.890 ms/op


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
# Warmup Iteration   1: 5.587 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.007 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.011 ms/op
Iteration   1: 3.944 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  14.516 ms/op
                 listUser·p0.9999: 16.789 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   2: 3.897 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.423 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.565 ms/op
                 listUser·p0.9999: 16.895 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   3: 3.892 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.122 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.923 ms/op
                 listUser·p0.9999: 16.934 ms/op
                 listUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245266
  mean =      3.911 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2573 
    [ 2.500,  3.750) = 104585 
    [ 3.750,  5.000) = 123372 
    [ 5.000,  6.250) = 9454 
    [ 6.250,  7.500) = 4115 
    [ 7.500,  8.750) = 476 
    [ 8.750, 10.000) = 177 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 182 
    [15.000, 16.250) = 120 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     14.696 ms/op
     p(99.9900) =     16.876 ms/op
     p(99.9990) =     18.746 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.197 ± 2.172  ops/ms
ClientGrpc.existUser                       thrpt       3  10.751 ± 1.571  ops/ms
ClientGrpc.getUser                         thrpt       3  10.457 ± 1.979  ops/ms
ClientGrpc.listUser                        thrpt       3   7.928 ± 1.686  ops/ms
ClientGrpc.createUser                       avgt       3   3.050 ± 0.717   ms/op
ClientGrpc.existUser                        avgt       3   3.002 ± 0.730   ms/op
ClientGrpc.getUser                          avgt       3   3.118 ± 1.001   ms/op
ClientGrpc.listUser                         avgt       3   3.946 ± 0.620   ms/op
ClientGrpc.createUser                     sample  305974   3.136 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.564           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.112           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.979           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.658           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.297           ms/op
ClientGrpc.existUser                      sample  317602   3.021 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.667           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.982           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.858           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.723           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.367           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.169           ms/op
ClientGrpc.getUser                        sample  311271   3.084 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.671           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.184           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.940           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.890           ms/op
ClientGrpc.listUser                       sample  245266   3.911 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.122           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.432           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.259           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.696           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.876           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.809           ms/op
