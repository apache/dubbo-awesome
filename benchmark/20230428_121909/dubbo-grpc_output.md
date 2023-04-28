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
# Warmup Iteration   1: 4.517 ops/ms
# Warmup Iteration   2: 9.130 ops/ms
# Warmup Iteration   3: 10.505 ops/ms
Iteration   1: 10.605 ops/ms
Iteration   2: 10.919 ops/ms
Iteration   3: 10.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.775 ±(99.9%) 2.894 ops/ms [Average]
  (min, avg, max) = (10.605, 10.775, 10.919), stdev = 0.159
  CI (99.9%): [7.881, 13.669] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.234 ops/ms
# Warmup Iteration   2: 10.706 ops/ms
# Warmup Iteration   3: 11.259 ops/ms
Iteration   1: 11.228 ops/ms
Iteration   2: 11.252 ops/ms
Iteration   3: 11.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.249 ±(99.9%) 0.371 ops/ms [Average]
  (min, avg, max) = (11.228, 11.249, 11.268), stdev = 0.020
  CI (99.9%): [10.878, 11.621] (assumes normal distribution)


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
# Warmup Iteration   1: 7.435 ops/ms
# Warmup Iteration   2: 10.113 ops/ms
# Warmup Iteration   3: 10.534 ops/ms
Iteration   1: 10.655 ops/ms
Iteration   2: 10.752 ops/ms
Iteration   3: 10.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.670 ±(99.9%) 1.387 ops/ms [Average]
  (min, avg, max) = (10.603, 10.670, 10.752), stdev = 0.076
  CI (99.9%): [9.284, 12.057] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.855 ops/ms
# Warmup Iteration   2: 8.126 ops/ms
# Warmup Iteration   3: 8.240 ops/ms
Iteration   1: 8.198 ops/ms
Iteration   2: 8.365 ops/ms
Iteration   3: 8.262 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.275 ±(99.9%) 1.534 ops/ms [Average]
  (min, avg, max) = (8.198, 8.275, 8.365), stdev = 0.084
  CI (99.9%): [6.741, 9.809] (assumes normal distribution)


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.005 ms/op
Iteration   1: 2.981 ±(99.9%) 0.001 ms/op
Iteration   2: 2.960 ±(99.9%) 0.003 ms/op
Iteration   3: 2.984 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.975 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.960, 2.975, 2.984), stdev = 0.013
  CI (99.9%): [2.731, 3.219] (assumes normal distribution)


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.940 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.944 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.003 ms/op
Iteration   2: 2.817 ±(99.9%) 0.004 ms/op
Iteration   3: 2.898 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 1.315 ms/op [Average]
  (min, avg, max) = (2.817, 2.892, 2.961), stdev = 0.072
  CI (99.9%): [1.577, 4.207] (assumes normal distribution)


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
# Warmup Iteration   1: 4.020 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.003 ms/op
Iteration   1: 2.964 ±(99.9%) 0.002 ms/op
Iteration   2: 3.021 ±(99.9%) 0.007 ms/op
Iteration   3: 2.940 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.975 ±(99.9%) 0.756 ms/op [Average]
  (min, avg, max) = (2.940, 2.975, 3.021), stdev = 0.041
  CI (99.9%): [2.219, 3.731] (assumes normal distribution)


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
# Warmup Iteration   1: 4.865 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.028 ms/op
Iteration   1: 3.916 ±(99.9%) 0.012 ms/op
Iteration   2: 3.884 ±(99.9%) 0.024 ms/op
Iteration   3: 3.899 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.899 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (3.884, 3.899, 3.916), stdev = 0.016
  CI (99.9%): [3.608, 4.190] (assumes normal distribution)


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  9.978 ms/op
                 createUser·p0.9999: 14.795 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  8.272 ms/op
                 createUser·p0.9999: 20.709 ms/op
                 createUser·p1.00:   20.939 ms/op

Iteration   3: 2.981 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.537 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  9.912 ms/op
                 createUser·p0.9999: 23.864 ms/op
                 createUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320034
  mean =      2.997 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29064 
    [ 2.500,  5.000) = 289298 
    [ 5.000,  7.500) = 1174 
    [ 7.500, 10.000) = 198 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      9.896 ms/op
     p(99.9900) =     21.657 ms/op
     p(99.9990) =     24.170 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 3.673 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.950 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.815 ±(99.9%) 0.006 ms/op
Iteration   1: 2.866 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.543 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.335 ms/op
                 existUser·p0.9999: 17.918 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   2: 2.871 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.021 ms/op
                 existUser·p0.9999: 33.157 ms/op
                 existUser·p1.00:   33.325 ms/op

Iteration   3: 2.822 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.524 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  10.625 ms/op
                 existUser·p0.9999: 14.352 ms/op
                 existUser·p1.00:   15.925 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336584
  mean =      2.853 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 52418 
    [ 2.500,  5.000) = 283082 
    [ 5.000,  7.500) = 623 
    [ 7.500, 10.000) = 206 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.535 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.526 ms/op
     p(99.9900) =     26.281 ms/op
     p(99.9990) =     33.280 ms/op
     p(99.9999) =     33.325 ms/op
    p(100.0000) =     33.325 ms/op


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
# Warmup Iteration   1: 3.963 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
Iteration   1: 2.964 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.334 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  8.005 ms/op
                 getUser·p0.9999: 11.685 ms/op
                 getUser·p1.00:   11.878 ms/op

Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.570 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.689 ms/op
                 getUser·p0.9999: 12.625 ms/op
                 getUser·p1.00:   13.009 ms/op

Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.658 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  11.252 ms/op
                 getUser·p0.9999: 14.633 ms/op
                 getUser·p1.00:   15.090 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323351
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1881 
    [ 1.250,  2.500) = 23935 
    [ 2.500,  3.750) = 284598 
    [ 3.750,  5.000) = 11506 
    [ 5.000,  6.250) = 832 
    [ 6.250,  7.500) = 188 
    [ 7.500,  8.750) = 141 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 128 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.156 ms/op
     p(99.9900) =     13.593 ms/op
     p(99.9990) =     15.033 ms/op
     p(99.9999) =     15.090 ms/op
    p(100.0000) =     15.090 ms/op


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
# Warmup Iteration   1: 5.349 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.010 ms/op
Iteration   1: 3.837 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.128 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.533 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  12.479 ms/op
                 listUser·p0.9999: 18.481 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   2: 3.801 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.485 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  13.102 ms/op
                 listUser·p0.9999: 14.578 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   3: 3.846 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  13.987 ms/op
                 listUser·p0.9999: 21.486 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 250583
  mean =      3.828 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5958 
    [ 2.500,  5.000) = 224047 
    [ 5.000,  7.500) = 19193 
    [ 7.500, 10.000) = 737 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.107 ms/op
     p(99.9900) =     21.037 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.775 ± 2.894  ops/ms
ClientGrpc.existUser                       thrpt       3  11.249 ± 0.371  ops/ms
ClientGrpc.getUser                         thrpt       3  10.670 ± 1.387  ops/ms
ClientGrpc.listUser                        thrpt       3   8.275 ± 1.534  ops/ms
ClientGrpc.createUser                       avgt       3   2.975 ± 0.244   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 1.315   ms/op
ClientGrpc.getUser                          avgt       3   2.975 ± 0.756   ms/op
ClientGrpc.listUser                         avgt       3   3.899 ± 0.291   ms/op
ClientGrpc.createUser                     sample  320034   2.997 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.537           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.974           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.896           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.657           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.379           ms/op
ClientGrpc.existUser                      sample  336584   2.853 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.495           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.526           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.281           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          33.325           ms/op
ClientGrpc.getUser                        sample  323351   2.967 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.564           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.457           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.156           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.593           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.090           ms/op
ClientGrpc.listUser                       sample  250583   3.828 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.485           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.431           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.107           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.037           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.758           ms/op
