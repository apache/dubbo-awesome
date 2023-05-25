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
# Warmup Iteration   1: 4.125 ops/ms
# Warmup Iteration   2: 9.266 ops/ms
# Warmup Iteration   3: 9.998 ops/ms
Iteration   1: 10.214 ops/ms
Iteration   2: 10.700 ops/ms
Iteration   3: 10.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.460 ±(99.9%) 4.433 ops/ms [Average]
  (min, avg, max) = (10.214, 10.460, 10.700), stdev = 0.243
  CI (99.9%): [6.027, 14.893] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.487 ops/ms
# Warmup Iteration   2: 10.492 ops/ms
# Warmup Iteration   3: 11.121 ops/ms
Iteration   1: 10.963 ops/ms
Iteration   2: 10.781 ops/ms
Iteration   3: 11.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.929 ±(99.9%) 2.463 ops/ms [Average]
  (min, avg, max) = (10.781, 10.929, 11.044), stdev = 0.135
  CI (99.9%): [8.466, 13.392] (assumes normal distribution)


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
# Warmup Iteration   1: 6.720 ops/ms
# Warmup Iteration   2: 10.128 ops/ms
# Warmup Iteration   3: 10.506 ops/ms
Iteration   1: 10.657 ops/ms
Iteration   2: 10.528 ops/ms
Iteration   3: 10.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.553 ±(99.9%) 1.698 ops/ms [Average]
  (min, avg, max) = (10.476, 10.553, 10.657), stdev = 0.093
  CI (99.9%): [8.856, 12.251] (assumes normal distribution)


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
# Warmup Iteration   1: 5.450 ops/ms
# Warmup Iteration   2: 7.864 ops/ms
# Warmup Iteration   3: 7.967 ops/ms
Iteration   1: 7.999 ops/ms
Iteration   2: 8.010 ops/ms
Iteration   3: 8.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.041 ±(99.9%) 1.159 ops/ms [Average]
  (min, avg, max) = (7.999, 8.041, 8.114), stdev = 0.064
  CI (99.9%): [6.882, 9.200] (assumes normal distribution)


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
# Warmup Iteration   1: 4.151 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 3.047 ±(99.9%) 0.003 ms/op
Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
Iteration   3: 3.124 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.083 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (3.047, 3.083, 3.124), stdev = 0.039
  CI (99.9%): [2.371, 3.794] (assumes normal distribution)


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
# Warmup Iteration   1: 3.895 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.927 ±(99.9%) 0.002 ms/op
Iteration   1: 2.896 ±(99.9%) 0.002 ms/op
Iteration   2: 2.894 ±(99.9%) 0.003 ms/op
Iteration   3: 2.884 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.891 ±(99.9%) 0.115 ms/op [Average]
  (min, avg, max) = (2.884, 2.891, 2.896), stdev = 0.006
  CI (99.9%): [2.776, 3.007] (assumes normal distribution)


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
# Warmup Iteration   1: 4.444 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.002 ms/op
Iteration   1: 3.023 ±(99.9%) 0.003 ms/op
Iteration   2: 3.024 ±(99.9%) 0.004 ms/op
Iteration   3: 3.045 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.031 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (3.023, 3.031, 3.045), stdev = 0.012
  CI (99.9%): [2.807, 3.254] (assumes normal distribution)


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
# Warmup Iteration   1: 5.549 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.966 ±(99.9%) 0.028 ms/op
Iteration   1: 3.887 ±(99.9%) 0.006 ms/op
Iteration   2: 4.003 ±(99.9%) 0.013 ms/op
Iteration   3: 3.972 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.954 ±(99.9%) 1.100 ms/op [Average]
  (min, avg, max) = (3.887, 3.954, 4.003), stdev = 0.060
  CI (99.9%): [2.854, 5.054] (assumes normal distribution)


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
# Warmup Iteration   1: 4.389 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  7.919 ms/op
                 createUser·p0.9999: 14.488 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.946 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  8.990 ms/op
                 createUser·p0.9999: 13.986 ms/op
                 createUser·p1.00:   14.500 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.765 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  12.730 ms/op
                 createUser·p0.9999: 26.783 ms/op
                 createUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316465
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25632 
    [ 2.500,  5.000) = 288950 
    [ 5.000,  7.500) = 1487 
    [ 7.500, 10.000) = 124 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.765 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      8.954 ms/op
     p(99.9900) =     26.216 ms/op
     p(99.9990) =     26.870 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.915 ±(99.9%) 0.005 ms/op
Iteration   1: 2.893 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  6.324 ms/op
                 existUser·p0.9999: 12.761 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   2: 2.865 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.298 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.180 ms/op
                 existUser·p0.9999: 13.318 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.899 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   3.920 ms/op
                 existUser·p0.999:  5.849 ms/op
                 existUser·p0.9999: 17.267 ms/op
                 existUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332427
  mean =      2.886 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1031 
    [ 1.250,  2.500) = 38069 
    [ 2.500,  3.750) = 285569 
    [ 3.750,  5.000) = 6913 
    [ 5.000,  6.250) = 541 
    [ 6.250,  7.500) = 139 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.298 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.039 ms/op
     p(99.9000) =      6.169 ms/op
     p(99.9900) =     15.446 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 4.223 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.812 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.944 ms/op
                 getUser·p0.9999: 12.941 ms/op
                 getUser·p1.00:   13.156 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  6.923 ms/op
                 getUser·p0.9999: 14.740 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   3: 2.998 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.613 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.368 ms/op
                 getUser·p0.9999: 15.882 ms/op
                 getUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319122
  mean =      3.008 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 571 
    [ 1.250,  2.500) = 21254 
    [ 2.500,  3.750) = 283620 
    [ 3.750,  5.000) = 12000 
    [ 5.000,  6.250) = 1148 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      6.873 ms/op
     p(99.9900) =     14.714 ms/op
     p(99.9990) =     16.070 ms/op
     p(99.9999) =     16.187 ms/op
    p(100.0000) =     16.187 ms/op


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
# Warmup Iteration   1: 4.819 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.116 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.010 ms/op
Iteration   1: 3.956 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  13.206 ms/op
                 listUser·p0.9999: 19.920 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.927 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.137 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  17.719 ms/op
                 listUser·p0.9999: 24.670 ms/op
                 listUser·p1.00:   27.197 ms/op

Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.102 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  15.281 ms/op
                 listUser·p0.9999: 17.788 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243911
  mean =      3.935 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4208 
    [ 2.500,  5.000) = 217979 
    [ 5.000,  7.500) = 20457 
    [ 7.500, 10.000) = 798 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     15.386 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     27.050 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.460 ± 4.433  ops/ms
ClientGrpc.existUser                       thrpt       3  10.929 ± 2.463  ops/ms
ClientGrpc.getUser                         thrpt       3  10.553 ± 1.698  ops/ms
ClientGrpc.listUser                        thrpt       3   8.041 ± 1.159  ops/ms
ClientGrpc.createUser                       avgt       3   3.083 ± 0.712   ms/op
ClientGrpc.existUser                        avgt       3   2.891 ± 0.115   ms/op
ClientGrpc.getUser                          avgt       3   3.031 ± 0.223   ms/op
ClientGrpc.listUser                         avgt       3   3.954 ± 1.100   ms/op
ClientGrpc.createUser                     sample  316465   3.033 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.765           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.678           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.954           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.216           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.296           ms/op
ClientGrpc.existUser                      sample  332427   2.886 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.298           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.039           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.169           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.446           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.990           ms/op
ClientGrpc.getUser                        sample  319122   3.008 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.613           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.465           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.612           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.873           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.714           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.187           ms/op
ClientGrpc.listUser                       sample  243911   3.935 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.102           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.386           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.855           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.197           ms/op
