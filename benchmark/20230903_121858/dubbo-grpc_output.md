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
# Warmup Iteration   1: 4.245 ops/ms
# Warmup Iteration   2: 8.693 ops/ms
# Warmup Iteration   3: 9.899 ops/ms
Iteration   1: 10.125 ops/ms
Iteration   2: 10.485 ops/ms
Iteration   3: 10.520 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.377 ±(99.9%) 3.986 ops/ms [Average]
  (min, avg, max) = (10.125, 10.377, 10.520), stdev = 0.218
  CI (99.9%): [6.391, 14.362] (assumes normal distribution)


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
# Warmup Iteration   1: 7.101 ops/ms
# Warmup Iteration   2: 10.464 ops/ms
# Warmup Iteration   3: 10.825 ops/ms
Iteration   1: 10.890 ops/ms
Iteration   2: 11.010 ops/ms
Iteration   3: 11.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.995 ±(99.9%) 1.791 ops/ms [Average]
  (min, avg, max) = (10.890, 10.995, 11.084), stdev = 0.098
  CI (99.9%): [9.204, 12.786] (assumes normal distribution)


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
# Warmup Iteration   1: 6.848 ops/ms
# Warmup Iteration   2: 9.988 ops/ms
# Warmup Iteration   3: 10.500 ops/ms
Iteration   1: 10.461 ops/ms
Iteration   2: 10.483 ops/ms
Iteration   3: 10.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.539 ±(99.9%) 2.122 ops/ms [Average]
  (min, avg, max) = (10.461, 10.539, 10.672), stdev = 0.116
  CI (99.9%): [8.416, 12.661] (assumes normal distribution)


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
# Warmup Iteration   1: 5.341 ops/ms
# Warmup Iteration   2: 7.809 ops/ms
# Warmup Iteration   3: 8.149 ops/ms
Iteration   1: 8.033 ops/ms
Iteration   2: 8.030 ops/ms
Iteration   3: 8.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.048 ±(99.9%) 0.525 ops/ms [Average]
  (min, avg, max) = (8.030, 8.048, 8.081), stdev = 0.029
  CI (99.9%): [7.523, 8.573] (assumes normal distribution)


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.222 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.002 ms/op
Iteration   1: 3.068 ±(99.9%) 0.003 ms/op
Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.061 ±(99.9%) 0.732 ms/op [Average]
  (min, avg, max) = (3.018, 3.061, 3.098), stdev = 0.040
  CI (99.9%): [2.329, 3.793] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.926 ±(99.9%) 0.003 ms/op
Iteration   1: 2.960 ±(99.9%) 0.002 ms/op
Iteration   2: 2.955 ±(99.9%) 0.001 ms/op
Iteration   3: 2.872 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.929 ±(99.9%) 0.904 ms/op [Average]
  (min, avg, max) = (2.872, 2.929, 2.960), stdev = 0.050
  CI (99.9%): [2.024, 3.833] (assumes normal distribution)


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
# Warmup Iteration   1: 4.380 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.003 ms/op
Iteration   1: 3.061 ±(99.9%) 0.003 ms/op
Iteration   2: 3.034 ±(99.9%) 0.003 ms/op
Iteration   3: 3.033 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.042 ±(99.9%) 0.290 ms/op [Average]
  (min, avg, max) = (3.033, 3.042, 3.061), stdev = 0.016
  CI (99.9%): [2.752, 3.333] (assumes normal distribution)


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
# Warmup Iteration   1: 5.610 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.021 ms/op
Iteration   1: 4.019 ±(99.9%) 0.034 ms/op
Iteration   2: 3.994 ±(99.9%) 0.016 ms/op
Iteration   3: 3.968 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.994 ±(99.9%) 0.467 ms/op [Average]
  (min, avg, max) = (3.968, 3.994, 4.019), stdev = 0.026
  CI (99.9%): [3.527, 4.461] (assumes normal distribution)


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
# Warmup Iteration   1: 4.305 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.007 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.397 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  8.536 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.413 ms/op

Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.414 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  10.142 ms/op
                 createUser·p0.9999: 18.526 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   3: 3.116 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.685 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.995 ms/op
                 createUser·p0.999:  19.300 ms/op
                 createUser·p0.9999: 23.641 ms/op
                 createUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312228
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24707 
    [ 2.500,  5.000) = 285002 
    [ 5.000,  7.500) = 1657 
    [ 7.500, 10.000) = 510 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.397 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.809 ms/op
     p(99.9000) =     10.662 ms/op
     p(99.9900) =     21.914 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.006 ms/op
Iteration   1: 2.889 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.701 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.384 ms/op
                 existUser·p0.999:  7.378 ms/op
                 existUser·p0.9999: 18.676 ms/op
                 existUser·p1.00:   19.137 ms/op

Iteration   2: 2.954 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.820 ms/op
                 existUser·p0.9999: 13.593 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   3: 2.897 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  12.861 ms/op
                 existUser·p0.9999: 16.219 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329580
  mean =      2.913 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3489 
    [ 1.250,  2.500) = 38408 
    [ 2.500,  3.750) = 277079 
    [ 3.750,  5.000) = 8679 
    [ 5.000,  6.250) = 906 
    [ 6.250,  7.500) = 552 
    [ 7.500,  8.750) = 224 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.412 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.094 ms/op
     p(99.9900) =     17.197 ms/op
     p(99.9990) =     19.029 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.760 ms/op
                 getUser·p0.999:  8.133 ms/op
                 getUser·p0.9999: 12.820 ms/op
                 getUser·p1.00:   16.089 ms/op

Iteration   2: 3.046 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.612 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.801 ms/op
                 getUser·p0.999:  11.658 ms/op
                 getUser·p0.9999: 15.859 ms/op
                 getUser·p1.00:   16.073 ms/op

Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  8.603 ms/op
                 getUser·p0.9999: 15.969 ms/op
                 getUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316282
  mean =      3.035 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 910 
    [ 1.250,  2.500) = 19561 
    [ 2.500,  3.750) = 279548 
    [ 3.750,  5.000) = 13680 
    [ 5.000,  6.250) = 1376 
    [ 6.250,  7.500) = 552 
    [ 7.500,  8.750) = 330 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 98 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.612 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      9.009 ms/op
     p(99.9900) =     15.817 ms/op
     p(99.9990) =     17.586 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 5.356 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.357 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.012 ms/op
Iteration   1: 4.087 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.348 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.956 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  15.267 ms/op
                 listUser·p0.9999: 22.790 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 4.009 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 31.851 ms/op
                 listUser·p1.00:   32.440 ms/op

Iteration   3: 4.076 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.970 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.225 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 22.975 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236752
  mean =      4.057 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4049 
    [ 2.500,  5.000) = 204607 
    [ 5.000,  7.500) = 26106 
    [ 7.500, 10.000) = 1524 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      6.021 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     17.416 ms/op
     p(99.9900) =     30.649 ms/op
     p(99.9990) =     32.359 ms/op
     p(99.9999) =     32.440 ms/op
    p(100.0000) =     32.440 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.377 ± 3.986  ops/ms
ClientGrpc.existUser                       thrpt       3  10.995 ± 1.791  ops/ms
ClientGrpc.getUser                         thrpt       3  10.539 ± 2.122  ops/ms
ClientGrpc.listUser                        thrpt       3   8.048 ± 0.525  ops/ms
ClientGrpc.createUser                       avgt       3   3.061 ± 0.732   ms/op
ClientGrpc.existUser                        avgt       3   2.929 ± 0.904   ms/op
ClientGrpc.getUser                          avgt       3   3.042 ± 0.290   ms/op
ClientGrpc.listUser                         avgt       3   3.994 ± 0.467   ms/op
ClientGrpc.createUser                     sample  312228   3.074 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.397           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.809           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.662           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.914           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.986           ms/op
ClientGrpc.existUser                      sample  329580   2.913 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.682           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.412           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.432           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.197           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.137           ms/op
ClientGrpc.getUser                        sample  316282   3.035 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.612           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.506           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.009           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.817           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.859           ms/op
ClientGrpc.listUser                       sample  236752   4.057 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.970           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.875           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.299           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.416           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.649           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.440           ms/op
