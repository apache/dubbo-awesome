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
# Warmup Iteration   1: 5.081 ops/ms
# Warmup Iteration   2: 9.376 ops/ms
# Warmup Iteration   3: 10.195 ops/ms
Iteration   1: 10.925 ops/ms
Iteration   2: 10.551 ops/ms
Iteration   3: 10.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.675 ±(99.9%) 3.954 ops/ms [Average]
  (min, avg, max) = (10.549, 10.675, 10.925), stdev = 0.217
  CI (99.9%): [6.721, 14.629] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.719 ops/ms
# Warmup Iteration   2: 10.863 ops/ms
# Warmup Iteration   3: 10.990 ops/ms
Iteration   1: 11.007 ops/ms
Iteration   2: 11.142 ops/ms
Iteration   3: 11.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.096 ±(99.9%) 1.404 ops/ms [Average]
  (min, avg, max) = (11.007, 11.096, 11.142), stdev = 0.077
  CI (99.9%): [9.692, 12.499] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.759 ops/ms
# Warmup Iteration   2: 10.339 ops/ms
# Warmup Iteration   3: 10.462 ops/ms
Iteration   1: 10.578 ops/ms
Iteration   2: 10.482 ops/ms
Iteration   3: 10.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.624 ±(99.9%) 3.107 ops/ms [Average]
  (min, avg, max) = (10.482, 10.624, 10.813), stdev = 0.170
  CI (99.9%): [7.517, 13.731] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.624 ops/ms
# Warmup Iteration   2: 7.912 ops/ms
# Warmup Iteration   3: 8.130 ops/ms
Iteration   1: 8.065 ops/ms
Iteration   2: 8.066 ops/ms
Iteration   3: 8.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.122 ±(99.9%) 1.810 ops/ms [Average]
  (min, avg, max) = (8.065, 8.122, 8.237), stdev = 0.099
  CI (99.9%): [6.313, 9.932] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.085 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 2.986 ±(99.9%) 0.003 ms/op
Iteration   2: 3.021 ±(99.9%) 0.002 ms/op
Iteration   3: 2.954 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.987 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (2.954, 2.987, 3.021), stdev = 0.034
  CI (99.9%): [2.369, 3.605] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.711 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 2.846 ±(99.9%) 0.003 ms/op
Iteration   1: 2.912 ±(99.9%) 0.002 ms/op
Iteration   2: 2.926 ±(99.9%) 0.002 ms/op
Iteration   3: 2.837 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.892 ±(99.9%) 0.872 ms/op [Average]
  (min, avg, max) = (2.837, 2.892, 2.926), stdev = 0.048
  CI (99.9%): [2.020, 3.763] (assumes normal distribution)


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
# Warmup Iteration   1: 3.813 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.012 ms/op
Iteration   1: 3.051 ±(99.9%) 0.003 ms/op
Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
Iteration   3: 3.053 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.052 ±(99.9%) 0.017 ms/op [Average]
  (min, avg, max) = (3.051, 3.052, 3.053), stdev = 0.001
  CI (99.9%): [3.035, 3.069] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.876 ±(99.9%) 0.020 ms/op
Iteration   1: 3.945 ±(99.9%) 0.018 ms/op
Iteration   2: 3.743 ±(99.9%) 0.019 ms/op
Iteration   3: 3.934 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.874 ±(99.9%) 2.074 ms/op [Average]
  (min, avg, max) = (3.743, 3.874, 3.945), stdev = 0.114
  CI (99.9%): [1.800, 5.948] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.933 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.007 ms/op
Iteration   1: 3.026 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  9.601 ms/op
                 createUser·p0.9999: 22.512 ms/op
                 createUser·p1.00:   22.970 ms/op

Iteration   2: 2.982 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  14.609 ms/op
                 createUser·p0.9999: 20.152 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  11.452 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319237
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28870 
    [ 2.500,  5.000) = 288329 
    [ 5.000,  7.500) = 1314 
    [ 7.500, 10.000) = 365 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =     11.514 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     22.741 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.930 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.851 ±(99.9%) 0.007 ms/op
Iteration   1: 2.918 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  9.028 ms/op
                 existUser·p0.9999: 12.977 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   2: 2.858 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.500 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.489 ms/op
                 existUser·p0.999:  8.054 ms/op
                 existUser·p0.9999: 14.412 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   3: 2.879 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 14.970 ms/op
                 existUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332771
  mean =      2.885 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3343 
    [ 1.250,  2.500) = 41100 
    [ 2.500,  3.750) = 274966 
    [ 3.750,  5.000) = 11538 
    [ 5.000,  6.250) = 877 
    [ 6.250,  7.500) = 419 
    [ 7.500,  8.750) = 233 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      8.503 ms/op
     p(99.9900) =     14.446 ms/op
     p(99.9990) =     15.418 ms/op
     p(99.9999) =     16.843 ms/op
    p(100.0000) =     16.843 ms/op


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
Iteration   1: 3.063 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  10.492 ms/op
                 getUser·p0.9999: 18.762 ms/op
                 getUser·p1.00:   18.973 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.548 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.379 ms/op
                 getUser·p0.9999: 12.868 ms/op
                 getUser·p1.00:   13.255 ms/op

Iteration   3: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.914 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  9.093 ms/op
                 getUser·p0.9999: 15.294 ms/op
                 getUser·p1.00:   15.729 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315344
  mean =      3.042 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1291 
    [ 1.250,  2.500) = 23833 
    [ 2.500,  3.750) = 269434 
    [ 3.750,  5.000) = 19013 
    [ 5.000,  6.250) = 853 
    [ 6.250,  7.500) = 368 
    [ 7.500,  8.750) = 188 
    [ 8.750, 10.000) = 118 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 93 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      9.077 ms/op
     p(99.9900) =     18.300 ms/op
     p(99.9990) =     18.897 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


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
# Warmup Iteration   1: 4.781 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.011 ms/op
Iteration   1: 3.992 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  12.883 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 3.891 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.642 ms/op
                 listUser·p0.999:  13.701 ms/op
                 listUser·p0.9999: 16.282 ms/op
                 listUser·p1.00:   17.695 ms/op

Iteration   3: 3.860 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.341 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.436 ms/op
                 listUser·p0.9999: 17.685 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245313
  mean =      3.913 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3517 
    [ 2.500,  5.000) = 221368 
    [ 5.000,  7.500) = 18871 
    [ 7.500, 10.000) = 949 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.817 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.939 ms/op
     p(99.9000) =     14.036 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     21.106 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.675 ± 3.954  ops/ms
ClientGrpc.existUser                       thrpt       3  11.096 ± 1.404  ops/ms
ClientGrpc.getUser                         thrpt       3  10.624 ± 3.107  ops/ms
ClientGrpc.listUser                        thrpt       3   8.122 ± 1.810  ops/ms
ClientGrpc.createUser                       avgt       3   2.987 ± 0.618   ms/op
ClientGrpc.existUser                        avgt       3   2.892 ± 0.872   ms/op
ClientGrpc.getUser                          avgt       3   3.052 ± 0.017   ms/op
ClientGrpc.listUser                         avgt       3   3.874 ± 2.074   ms/op
ClientGrpc.createUser                     sample  319237   3.006 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.613           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.514           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.742           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.970           ms/op
ClientGrpc.existUser                      sample  332771   2.885 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.500           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.503           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.446           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.843           ms/op
ClientGrpc.getUser                        sample  315344   3.042 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.548           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.077           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.300           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.973           ms/op
ClientGrpc.listUser                       sample  245313   3.913 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.827           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.817           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.939           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.036           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.792           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.201           ms/op
