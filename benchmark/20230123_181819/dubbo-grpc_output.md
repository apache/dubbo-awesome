# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.433 ops/ms
# Warmup Iteration   2: 8.994 ops/ms
# Warmup Iteration   3: 9.979 ops/ms
Iteration   1: 10.170 ops/ms
Iteration   2: 9.851 ops/ms
Iteration   3: 9.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.926 ±(99.9%) 3.962 ops/ms [Average]
  (min, avg, max) = (9.756, 9.926, 10.170), stdev = 0.217
  CI (99.9%): [5.964, 13.887] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.699 ops/ms
# Warmup Iteration   2: 10.507 ops/ms
# Warmup Iteration   3: 10.695 ops/ms
Iteration   1: 10.523 ops/ms
Iteration   2: 10.339 ops/ms
Iteration   3: 10.591 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.484 ±(99.9%) 2.375 ops/ms [Average]
  (min, avg, max) = (10.339, 10.484, 10.591), stdev = 0.130
  CI (99.9%): [8.109, 12.859] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.847 ops/ms
# Warmup Iteration   2: 10.006 ops/ms
# Warmup Iteration   3: 9.981 ops/ms
Iteration   1: 9.953 ops/ms
Iteration   2: 9.993 ops/ms
Iteration   3: 10.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.989 ±(99.9%) 0.629 ops/ms [Average]
  (min, avg, max) = (9.953, 9.989, 10.022), stdev = 0.035
  CI (99.9%): [9.360, 10.619] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.179 ops/ms
# Warmup Iteration   2: 7.397 ops/ms
# Warmup Iteration   3: 7.721 ops/ms
Iteration   1: 7.877 ops/ms
Iteration   2: 7.829 ops/ms
Iteration   3: 7.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.772 ±(99.9%) 2.596 ops/ms [Average]
  (min, avg, max) = (7.610, 7.772, 7.877), stdev = 0.142
  CI (99.9%): [5.176, 10.368] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.620 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.003 ms/op
Iteration   1: 3.143 ±(99.9%) 0.004 ms/op
Iteration   2: 3.196 ±(99.9%) 0.003 ms/op
Iteration   3: 3.190 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.176 ±(99.9%) 0.528 ms/op [Average]
  (min, avg, max) = (3.143, 3.176, 3.196), stdev = 0.029
  CI (99.9%): [2.648, 3.704] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.902 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.002 ms/op
Iteration   1: 3.121 ±(99.9%) 0.002 ms/op
Iteration   2: 3.065 ±(99.9%) 0.003 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.081 ±(99.9%) 0.637 ms/op [Average]
  (min, avg, max) = (3.058, 3.081, 3.121), stdev = 0.035
  CI (99.9%): [2.444, 3.718] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.622 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.224 ±(99.9%) 0.003 ms/op
Iteration   1: 3.190 ±(99.9%) 0.003 ms/op
Iteration   2: 3.218 ±(99.9%) 0.002 ms/op
Iteration   3: 3.126 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.178 ±(99.9%) 0.859 ms/op [Average]
  (min, avg, max) = (3.126, 3.178, 3.218), stdev = 0.047
  CI (99.9%): [2.319, 4.037] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.511 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 4.139 ±(99.9%) 0.012 ms/op
Iteration   1: 4.080 ±(99.9%) 0.031 ms/op
Iteration   2: 3.988 ±(99.9%) 0.014 ms/op
Iteration   3: 3.996 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.021 ±(99.9%) 0.933 ms/op [Average]
  (min, avg, max) = (3.988, 4.021, 4.080), stdev = 0.051
  CI (99.9%): [3.088, 4.954] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.503 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.006 ms/op
Iteration   1: 3.177 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  7.450 ms/op
                 createUser·p0.9999: 12.741 ms/op
                 createUser·p1.00:   13.025 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  6.668 ms/op
                 createUser·p0.9999: 13.337 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.945 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  13.082 ms/op
                 createUser·p0.9999: 16.949 ms/op
                 createUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301456
  mean =      3.186 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 363 
    [ 1.250,  2.500) = 17196 
    [ 2.500,  3.750) = 246286 
    [ 3.750,  5.000) = 35972 
    [ 5.000,  6.250) = 934 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 139 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 51 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      4.604 ms/op
     p(99.9000) =     10.715 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     17.137 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.181 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.006 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.668 ms/op
                 existUser·p0.9999: 13.704 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.289 ms/op
                 existUser·p0.9999: 14.293 ms/op
                 existUser·p1.00:   16.777 ms/op

Iteration   3: 2.969 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.639 ms/op
                 existUser·p0.9999: 17.178 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319658
  mean =      3.004 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2055 
    [ 1.250,  2.500) = 38828 
    [ 2.500,  3.750) = 254357 
    [ 3.750,  5.000) = 23246 
    [ 5.000,  6.250) = 640 
    [ 6.250,  7.500) = 310 
    [ 7.500,  8.750) = 61 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.898 ms/op
     p(99.9900) =     16.146 ms/op
     p(99.9990) =     17.524 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.164 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.147 ±(99.9%) 0.006 ms/op
Iteration   1: 3.236 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.269 ms/op
                 getUser·p0.9999: 13.402 ms/op
                 getUser·p1.00:   13.599 ms/op

Iteration   2: 3.149 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.490 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.067 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.900 ms/op
                 getUser·p0.9999: 14.415 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.675 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  10.122 ms/op
                 getUser·p0.9999: 16.294 ms/op
                 getUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302923
  mean =      3.168 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 378 
    [ 1.250,  2.500) = 18324 
    [ 2.500,  3.750) = 247403 
    [ 3.750,  5.000) = 35357 
    [ 5.000,  6.250) = 766 
    [ 6.250,  7.500) = 371 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 68 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.669 ms/op
     p(99.9900) =     15.183 ms/op
     p(99.9990) =     16.970 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.234 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.011 ms/op
Iteration   1: 4.164 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.750 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.185 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 19.015 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 4.085 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 25.597 ms/op
                 listUser·p1.00:   29.032 ms/op

Iteration   3: 4.111 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 28.818 ms/op
                 listUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232947
  mean =      4.120 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2251 
    [ 2.500,  5.000) = 201185 
    [ 5.000,  7.500) = 28016 
    [ 7.500, 10.000) = 1026 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     15.746 ms/op
     p(99.9900) =     27.889 ms/op
     p(99.9990) =     29.164 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.926 ± 3.962  ops/ms
ClientGrpc.existUser                       thrpt       3  10.484 ± 2.375  ops/ms
ClientGrpc.getUser                         thrpt       3   9.989 ± 0.629  ops/ms
ClientGrpc.listUser                        thrpt       3   7.772 ± 2.596  ops/ms
ClientGrpc.createUser                       avgt       3   3.176 ± 0.528   ms/op
ClientGrpc.existUser                        avgt       3   3.081 ± 0.637   ms/op
ClientGrpc.getUser                          avgt       3   3.178 ± 0.859   ms/op
ClientGrpc.listUser                         avgt       3   4.021 ± 0.933   ms/op
ClientGrpc.createUser                     sample  301456   3.186 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.734           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.838           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.088           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.715           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.777           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.269           ms/op
ClientGrpc.existUser                      sample  319658   3.004 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.594           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.898           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.146           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.531           ms/op
ClientGrpc.getUser                        sample  302923   3.168 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.490           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.051           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.669           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.183           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.236           ms/op
ClientGrpc.listUser                       sample  232947   4.120 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.750           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.936           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.746           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.889           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.229           ms/op
