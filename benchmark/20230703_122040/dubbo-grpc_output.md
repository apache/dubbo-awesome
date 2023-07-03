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
# Warmup Iteration   1: 3.379 ops/ms
# Warmup Iteration   2: 8.398 ops/ms
# Warmup Iteration   3: 10.195 ops/ms
Iteration   1: 10.367 ops/ms
Iteration   2: 10.393 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.400 ±(99.9%) 0.685 ops/ms [Average]
  (min, avg, max) = (10.367, 10.400, 10.441), stdev = 0.038
  CI (99.9%): [9.716, 11.085] (assumes normal distribution)


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
# Warmup Iteration   1: 7.781 ops/ms
# Warmup Iteration   2: 10.322 ops/ms
# Warmup Iteration   3: 10.806 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 10.852 ops/ms
Iteration   3: 10.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.781 ±(99.9%) 1.669 ops/ms [Average]
  (min, avg, max) = (10.678, 10.781, 10.852), stdev = 0.091
  CI (99.9%): [9.112, 12.450] (assumes normal distribution)


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
# Warmup Iteration   1: 6.601 ops/ms
# Warmup Iteration   2: 10.039 ops/ms
# Warmup Iteration   3: 10.294 ops/ms
Iteration   1: 10.413 ops/ms
Iteration   2: 10.467 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.495 ±(99.9%) 1.800 ops/ms [Average]
  (min, avg, max) = (10.413, 10.495, 10.604), stdev = 0.099
  CI (99.9%): [8.695, 12.295] (assumes normal distribution)


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
# Warmup Iteration   1: 5.213 ops/ms
# Warmup Iteration   2: 8.212 ops/ms
# Warmup Iteration   3: 7.931 ops/ms
Iteration   1: 8.035 ops/ms
Iteration   2: 7.932 ops/ms
Iteration   3: 8.228 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.065 ±(99.9%) 2.737 ops/ms [Average]
  (min, avg, max) = (7.932, 8.065, 8.228), stdev = 0.150
  CI (99.9%): [5.328, 10.802] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.483 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.002 ms/op
Iteration   1: 3.124 ±(99.9%) 0.003 ms/op
Iteration   2: 3.087 ±(99.9%) 0.002 ms/op
Iteration   3: 3.035 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.082 ±(99.9%) 0.811 ms/op [Average]
  (min, avg, max) = (3.035, 3.082, 3.124), stdev = 0.044
  CI (99.9%): [2.271, 3.893] (assumes normal distribution)


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.002 ms/op
Iteration   1: 2.960 ±(99.9%) 0.002 ms/op
Iteration   2: 2.926 ±(99.9%) 0.003 ms/op
Iteration   3: 2.937 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.941 ±(99.9%) 0.323 ms/op [Average]
  (min, avg, max) = (2.926, 2.941, 2.960), stdev = 0.018
  CI (99.9%): [2.618, 3.264] (assumes normal distribution)


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
# Warmup Iteration   1: 4.473 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.001 ms/op
Iteration   1: 3.033 ±(99.9%) 0.002 ms/op
Iteration   2: 3.066 ±(99.9%) 0.003 ms/op
Iteration   3: 3.068 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.056 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.033, 3.056, 3.068), stdev = 0.020
  CI (99.9%): [2.691, 3.421] (assumes normal distribution)


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
# Warmup Iteration   1: 5.475 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.018 ms/op
Iteration   1: 3.950 ±(99.9%) 0.015 ms/op
Iteration   2: 3.943 ±(99.9%) 0.016 ms/op
Iteration   3: 4.013 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.969 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (3.943, 3.969, 4.013), stdev = 0.039
  CI (99.9%): [3.262, 4.676] (assumes normal distribution)


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
# Warmup Iteration   1: 4.625 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  6.955 ms/op
                 createUser·p0.9999: 13.657 ms/op
                 createUser·p1.00:   16.204 ms/op

Iteration   2: 3.062 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.940 ms/op
                 createUser·p0.9999: 18.973 ms/op
                 createUser·p1.00:   19.038 ms/op

Iteration   3: 3.083 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.760 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  12.517 ms/op
                 createUser·p0.9999: 29.708 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312808
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16443 
    [ 2.500,  5.000) = 295158 
    [ 5.000,  7.500) = 797 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.251 ms/op
     p(99.9000) =      9.856 ms/op
     p(99.9900) =     28.499 ms/op
     p(99.9990) =     30.273 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 4.251 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.960 ±(99.9%) 0.005 ms/op
Iteration   1: 2.905 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  7.493 ms/op
                 existUser·p0.9999: 12.714 ms/op
                 existUser·p1.00:   12.976 ms/op

Iteration   2: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.359 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.725 ms/op
                 existUser·p0.9999: 13.655 ms/op
                 existUser·p1.00:   14.270 ms/op

Iteration   3: 2.930 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.613 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  11.696 ms/op
                 existUser·p0.9999: 18.481 ms/op
                 existUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327905
  mean =      2.928 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 803 
    [ 1.250,  2.500) = 30392 
    [ 2.500,  3.750) = 287170 
    [ 3.750,  5.000) = 8365 
    [ 5.000,  6.250) = 683 
    [ 6.250,  7.500) = 145 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 85 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      8.311 ms/op
     p(99.9900) =     16.699 ms/op
     p(99.9990) =     18.594 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
Iteration   1: 3.045 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.831 ms/op
                 getUser·p0.9999: 13.975 ms/op
                 getUser·p1.00:   14.336 ms/op

Iteration   2: 3.008 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  7.102 ms/op
                 getUser·p0.9999: 14.610 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   3: 3.037 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.660 ms/op
                 getUser·p0.9999: 17.350 ms/op
                 getUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316791
  mean =      3.030 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 826 
    [ 1.250,  2.500) = 18174 
    [ 2.500,  3.750) = 283798 
    [ 3.750,  5.000) = 12422 
    [ 5.000,  6.250) = 1013 
    [ 6.250,  7.500) = 302 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 88 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.250 ms/op
     p(99.9900) =     16.619 ms/op
     p(99.9990) =     17.815 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 5.080 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.247 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.011 ms/op
Iteration   1: 4.047 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  15.086 ms/op
                 listUser·p0.9999: 22.217 ms/op
                 listUser·p1.00:   22.610 ms/op

Iteration   2: 4.029 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.081 ms/op
                 listUser·p0.9999: 22.775 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   3: 3.975 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.177 ms/op
                 listUser·p0.9999: 20.409 ms/op
                 listUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239027
  mean =      4.017 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1882 
    [ 2.500,  5.000) = 215652 
    [ 5.000,  7.500) = 20085 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     22.217 ms/op
     p(99.9990) =     23.620 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.400 ± 0.685  ops/ms
ClientGrpc.existUser                       thrpt       3  10.781 ± 1.669  ops/ms
ClientGrpc.getUser                         thrpt       3  10.495 ± 1.800  ops/ms
ClientGrpc.listUser                        thrpt       3   8.065 ± 2.737  ops/ms
ClientGrpc.createUser                       avgt       3   3.082 ± 0.811   ms/op
ClientGrpc.existUser                        avgt       3   2.941 ± 0.323   ms/op
ClientGrpc.getUser                          avgt       3   3.056 ± 0.365   ms/op
ClientGrpc.listUser                         avgt       3   3.969 ± 0.707   ms/op
ClientGrpc.createUser                     sample  312808   3.068 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.601           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.756           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.251           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.856           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.499           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.671           ms/op
ClientGrpc.existUser                      sample  327905   2.928 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.635           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.311           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.699           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.711           ms/op
ClientGrpc.getUser                        sample  316791   3.030 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.641           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.250           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.619           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.957           ms/op
ClientGrpc.listUser                       sample  239027   4.017 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.937           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.899           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.778           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.217           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.724           ms/op
