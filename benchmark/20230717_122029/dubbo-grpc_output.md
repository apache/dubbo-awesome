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
# Warmup Iteration   1: 3.952 ops/ms
# Warmup Iteration   2: 8.850 ops/ms
# Warmup Iteration   3: 9.973 ops/ms
Iteration   1: 10.543 ops/ms
Iteration   2: 10.809 ops/ms
Iteration   3: 10.258 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.537 ±(99.9%) 5.028 ops/ms [Average]
  (min, avg, max) = (10.258, 10.537, 10.809), stdev = 0.276
  CI (99.9%): [5.509, 15.565] (assumes normal distribution)


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
# Warmup Iteration   1: 7.375 ops/ms
# Warmup Iteration   2: 10.629 ops/ms
# Warmup Iteration   3: 10.867 ops/ms
Iteration   1: 11.138 ops/ms
Iteration   2: 11.041 ops/ms
Iteration   3: 11.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.096 ±(99.9%) 0.902 ops/ms [Average]
  (min, avg, max) = (11.041, 11.096, 11.138), stdev = 0.049
  CI (99.9%): [10.193, 11.998] (assumes normal distribution)


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
# Warmup Iteration   1: 6.554 ops/ms
# Warmup Iteration   2: 9.988 ops/ms
# Warmup Iteration   3: 10.442 ops/ms
Iteration   1: 10.274 ops/ms
Iteration   2: 10.401 ops/ms
Iteration   3: 10.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.365 ±(99.9%) 1.447 ops/ms [Average]
  (min, avg, max) = (10.274, 10.365, 10.421), stdev = 0.079
  CI (99.9%): [8.918, 11.813] (assumes normal distribution)


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
# Warmup Iteration   1: 5.120 ops/ms
# Warmup Iteration   2: 7.556 ops/ms
# Warmup Iteration   3: 7.540 ops/ms
Iteration   1: 7.772 ops/ms
Iteration   2: 7.990 ops/ms
Iteration   3: 7.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.846 ±(99.9%) 2.278 ops/ms [Average]
  (min, avg, max) = (7.772, 7.846, 7.990), stdev = 0.125
  CI (99.9%): [5.568, 10.124] (assumes normal distribution)


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
# Warmup Iteration   1: 4.478 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.003 ms/op
Iteration   1: 3.031 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.054 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.050 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (3.031, 3.050, 3.064), stdev = 0.017
  CI (99.9%): [2.741, 3.358] (assumes normal distribution)


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
# Warmup Iteration   1: 4.009 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.001 ms/op
Iteration   1: 2.945 ±(99.9%) 0.002 ms/op
Iteration   2: 2.907 ±(99.9%) 0.002 ms/op
Iteration   3: 2.916 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.923 ±(99.9%) 0.360 ms/op [Average]
  (min, avg, max) = (2.907, 2.923, 2.945), stdev = 0.020
  CI (99.9%): [2.563, 3.282] (assumes normal distribution)


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
# Warmup Iteration   1: 4.601 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.002 ms/op
Iteration   1: 3.066 ±(99.9%) 0.003 ms/op
Iteration   2: 3.083 ±(99.9%) 0.003 ms/op
Iteration   3: 3.095 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.081 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.066, 3.081, 3.095), stdev = 0.015
  CI (99.9%): [2.813, 3.350] (assumes normal distribution)


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
# Warmup Iteration   1: 6.306 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.041 ms/op
Iteration   1: 4.063 ±(99.9%) 0.030 ms/op
Iteration   2: 4.158 ±(99.9%) 0.015 ms/op
Iteration   3: 4.043 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.088 ±(99.9%) 1.125 ms/op [Average]
  (min, avg, max) = (4.043, 4.088, 4.158), stdev = 0.062
  CI (99.9%): [2.963, 5.213] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.623 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.007 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  9.501 ms/op
                 createUser·p0.9999: 19.608 ms/op
                 createUser·p1.00:   20.054 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  7.767 ms/op
                 createUser·p0.9999: 14.851 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.646 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  8.604 ms/op
                 createUser·p0.9999: 17.158 ms/op
                 createUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312802
  mean =      3.067 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19326 
    [ 2.500,  5.000) = 291717 
    [ 5.000,  7.500) = 1381 
    [ 7.500, 10.000) = 129 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =      8.356 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     19.919 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.161 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.920 ±(99.9%) 0.006 ms/op
Iteration   1: 2.938 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  6.145 ms/op
                 existUser·p0.9999: 12.304 ms/op
                 existUser·p1.00:   12.517 ms/op

Iteration   2: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.576 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  6.681 ms/op
                 existUser·p0.9999: 14.565 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.961 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  6.570 ms/op
                 existUser·p0.9999: 18.356 ms/op
                 existUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327259
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 729 
    [ 1.250,  2.500) = 33539 
    [ 2.500,  3.750) = 282639 
    [ 3.750,  5.000) = 9658 
    [ 5.000,  6.250) = 341 
    [ 6.250,  7.500) = 178 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      6.412 ms/op
     p(99.9900) =     16.884 ms/op
     p(99.9990) =     18.594 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 4.671 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.239 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.938 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.481 ms/op
                 getUser·p0.999:  9.620 ms/op
                 getUser·p0.9999: 14.153 ms/op
                 getUser·p1.00:   14.533 ms/op

Iteration   2: 3.123 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.000 ms/op
                 getUser·p0.9999: 18.776 ms/op
                 getUser·p1.00:   20.578 ms/op

Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.660 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.043 ms/op
                 getUser·p0.9999: 16.646 ms/op
                 getUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309668
  mean =      3.100 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15885 
    [ 2.500,  5.000) = 292412 
    [ 5.000,  7.500) = 1043 
    [ 7.500, 10.000) = 143 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.875 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.799 ms/op
     p(99.9900) =     18.056 ms/op
     p(99.9990) =     20.366 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.882 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.012 ms/op
Iteration   1: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.516 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.360 ms/op
                 listUser·p0.9999: 16.910 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 4.095 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.167 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  17.596 ms/op
                 listUser·p0.9999: 29.155 ms/op
                 listUser·p1.00:   30.114 ms/op

Iteration   3: 4.014 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.796 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  16.185 ms/op
                 listUser·p0.9999: 22.251 ms/op
                 listUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237320
  mean =      4.046 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1930 
    [ 2.500,  5.000) = 211913 
    [ 5.000,  7.500) = 22039 
    [ 7.500, 10.000) = 966 
    [10.000, 12.500) = 71 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.784 ms/op
     p(99.0000) =      7.076 ms/op
     p(99.9000) =     15.335 ms/op
     p(99.9900) =     28.198 ms/op
     p(99.9990) =     30.053 ms/op
     p(99.9999) =     30.114 ms/op
    p(100.0000) =     30.114 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.537 ± 5.028  ops/ms
ClientGrpc.existUser                       thrpt       3  11.096 ± 0.902  ops/ms
ClientGrpc.getUser                         thrpt       3  10.365 ± 1.447  ops/ms
ClientGrpc.listUser                        thrpt       3   7.846 ± 2.278  ops/ms
ClientGrpc.createUser                       avgt       3   3.050 ± 0.308   ms/op
ClientGrpc.existUser                        avgt       3   2.923 ± 0.360   ms/op
ClientGrpc.getUser                          avgt       3   3.081 ± 0.269   ms/op
ClientGrpc.listUser                         avgt       3   4.088 ± 1.125   ms/op
ClientGrpc.createUser                     sample  312802   3.067 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.646           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.356           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.776           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.054           ms/op
ClientGrpc.existUser                      sample  327259   2.935 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.744           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.412           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.884           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.743           ms/op
ClientGrpc.getUser                        sample  309668   3.100 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.660           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.799           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.056           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.578           ms/op
ClientGrpc.listUser                       sample  237320   4.046 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.796           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.879           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.076           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.335           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.198           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.114           ms/op
