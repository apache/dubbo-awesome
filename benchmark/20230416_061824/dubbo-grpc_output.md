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
# Warmup Iteration   1: 3.902 ops/ms
# Warmup Iteration   2: 8.582 ops/ms
# Warmup Iteration   3: 9.852 ops/ms
Iteration   1: 10.137 ops/ms
Iteration   2: 10.286 ops/ms
Iteration   3: 10.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.260 ±(99.9%) 2.035 ops/ms [Average]
  (min, avg, max) = (10.137, 10.260, 10.356), stdev = 0.112
  CI (99.9%): [8.224, 12.295] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.958 ops/ms
# Warmup Iteration   2: 10.414 ops/ms
# Warmup Iteration   3: 10.918 ops/ms
Iteration   1: 10.807 ops/ms
Iteration   2: 10.780 ops/ms
Iteration   3: 11.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.867 ±(99.9%) 2.318 ops/ms [Average]
  (min, avg, max) = (10.780, 10.867, 11.013), stdev = 0.127
  CI (99.9%): [8.549, 13.185] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 7.419 ops/ms
# Warmup Iteration   2: 9.676 ops/ms
# Warmup Iteration   3: 10.399 ops/ms
Iteration   1: 10.440 ops/ms
Iteration   2: 10.527 ops/ms
Iteration   3: 10.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.451 ±(99.9%) 1.286 ops/ms [Average]
  (min, avg, max) = (10.388, 10.451, 10.527), stdev = 0.070
  CI (99.9%): [9.166, 11.737] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.500 ops/ms
# Warmup Iteration   2: 7.551 ops/ms
# Warmup Iteration   3: 7.756 ops/ms
Iteration   1: 7.889 ops/ms
Iteration   2: 7.912 ops/ms
Iteration   3: 8.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.968 ±(99.9%) 2.152 ops/ms [Average]
  (min, avg, max) = (7.889, 7.968, 8.104), stdev = 0.118
  CI (99.9%): [5.817, 10.120] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.525 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.292 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.003 ms/op
Iteration   1: 3.120 ±(99.9%) 0.002 ms/op
Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
Iteration   3: 3.122 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.106 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (3.076, 3.106, 3.122), stdev = 0.026
  CI (99.9%): [2.636, 3.576] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.180 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.996 ±(99.9%) 0.003 ms/op
Iteration   1: 2.939 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.003 ms/op
Iteration   3: 2.982 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.976 ±(99.9%) 0.642 ms/op [Average]
  (min, avg, max) = (2.939, 2.976, 3.008), stdev = 0.035
  CI (99.9%): [2.334, 3.618] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.349 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.305 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.003 ms/op
Iteration   1: 3.167 ±(99.9%) 0.003 ms/op
Iteration   2: 3.165 ±(99.9%) 0.003 ms/op
Iteration   3: 3.074 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.135 ±(99.9%) 0.972 ms/op [Average]
  (min, avg, max) = (3.074, 3.135, 3.167), stdev = 0.053
  CI (99.9%): [2.163, 4.107] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.492 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.024 ms/op
Iteration   1: 4.047 ±(99.9%) 0.011 ms/op
Iteration   2: 4.022 ±(99.9%) 0.019 ms/op
Iteration   3: 4.003 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.024 ±(99.9%) 0.404 ms/op [Average]
  (min, avg, max) = (4.003, 4.024, 4.047), stdev = 0.022
  CI (99.9%): [3.620, 4.429] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.725 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.342 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.006 ms/op
Iteration   1: 3.064 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.735 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  9.576 ms/op
                 createUser·p0.9999: 14.198 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 3.093 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.277 ms/op
                 createUser·p0.9999: 24.237 ms/op
                 createUser·p1.00:   25.657 ms/op

Iteration   3: 3.148 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.858 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 23.233 ms/op
                 createUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309815
  mean =      3.101 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15999 
    [ 2.500,  5.000) = 292036 
    [ 5.000,  7.500) = 1276 
    [ 7.500, 10.000) = 205 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.735 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      9.817 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     24.602 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.236 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.980 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.006 ms/op
                 existUser·p0.9999: 14.512 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   2: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  10.068 ms/op
                 existUser·p0.9999: 16.243 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  9.240 ms/op
                 existUser·p0.9999: 17.531 ms/op
                 existUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321731
  mean =      2.983 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1021 
    [ 1.250,  2.500) = 31952 
    [ 2.500,  3.750) = 272339 
    [ 3.750,  5.000) = 14618 
    [ 5.000,  6.250) = 877 
    [ 6.250,  7.500) = 322 
    [ 7.500,  8.750) = 259 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.999 ms/op
     p(99.9900) =     16.843 ms/op
     p(99.9990) =     19.195 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.482 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  7.548 ms/op
                 getUser·p0.9999: 14.763 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.592 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.794 ms/op
                 getUser·p0.999:  9.592 ms/op
                 getUser·p0.9999: 18.317 ms/op
                 getUser·p1.00:   18.416 ms/op

Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.792 ms/op
                 getUser·p0.999:  8.390 ms/op
                 getUser·p0.9999: 19.562 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312567
  mean =      3.074 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 376 
    [ 1.250,  2.500) = 17994 
    [ 2.500,  3.750) = 275079 
    [ 3.750,  5.000) = 16974 
    [ 5.000,  6.250) = 1414 
    [ 6.250,  7.500) = 288 
    [ 7.500,  8.750) = 147 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      8.391 ms/op
     p(99.9900) =     18.735 ms/op
     p(99.9990) =     19.595 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 5.531 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.169 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.012 ms/op
Iteration   1: 3.993 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.495 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  14.744 ms/op
                 listUser·p0.9999: 18.644 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.033 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.095 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  15.541 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 3.999 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.603 ms/op
                 listUser·p0.999:  19.431 ms/op
                 listUser·p0.9999: 23.200 ms/op
                 listUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238882
  mean =      4.020 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2444 
    [ 2.500,  5.000) = 210739 
    [ 5.000,  7.500) = 23565 
    [ 7.500, 10.000) = 1577 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      7.348 ms/op
     p(99.9000) =     16.353 ms/op
     p(99.9900) =     22.486 ms/op
     p(99.9990) =     23.771 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.260 ± 2.035  ops/ms
ClientGrpc.existUser                       thrpt       3  10.867 ± 2.318  ops/ms
ClientGrpc.getUser                         thrpt       3  10.451 ± 1.286  ops/ms
ClientGrpc.listUser                        thrpt       3   7.968 ± 2.152  ops/ms
ClientGrpc.createUser                       avgt       3   3.106 ± 0.470   ms/op
ClientGrpc.existUser                        avgt       3   2.976 ± 0.642   ms/op
ClientGrpc.getUser                          avgt       3   3.135 ± 0.972   ms/op
ClientGrpc.listUser                         avgt       3   4.024 ± 0.404   ms/op
ClientGrpc.createUser                     sample  309815   3.101 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.735           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.617           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.854           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.817           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.855           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.657           ms/op
ClientGrpc.existUser                      sample  321731   2.983 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.714           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.999           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.843           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.300           ms/op
ClientGrpc.getUser                        sample  312567   3.074 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.839           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.391           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.735           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.661           ms/op
ClientGrpc.listUser                       sample  238882   4.020 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.982           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.980           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.348           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.353           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.486           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.953           ms/op
