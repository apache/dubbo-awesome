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
# Warmup Iteration   1: 4.095 ops/ms
# Warmup Iteration   2: 8.998 ops/ms
# Warmup Iteration   3: 9.745 ops/ms
Iteration   1: 10.096 ops/ms
Iteration   2: 9.917 ops/ms
Iteration   3: 9.729 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.914 ±(99.9%) 3.351 ops/ms [Average]
  (min, avg, max) = (9.729, 9.914, 10.096), stdev = 0.184
  CI (99.9%): [6.563, 13.265] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.051 ops/ms
# Warmup Iteration   2: 10.194 ops/ms
# Warmup Iteration   3: 10.304 ops/ms
Iteration   1: 10.353 ops/ms
Iteration   2: 10.390 ops/ms
Iteration   3: 10.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.419 ±(99.9%) 1.548 ops/ms [Average]
  (min, avg, max) = (10.353, 10.419, 10.515), stdev = 0.085
  CI (99.9%): [8.871, 11.968] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.672 ops/ms
# Warmup Iteration   2: 9.902 ops/ms
# Warmup Iteration   3: 10.028 ops/ms
Iteration   1: 10.084 ops/ms
Iteration   2: 9.925 ops/ms
Iteration   3: 10.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.020 ±(99.9%) 1.536 ops/ms [Average]
  (min, avg, max) = (9.925, 10.020, 10.084), stdev = 0.084
  CI (99.9%): [8.485, 11.556] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.955 ops/ms
# Warmup Iteration   2: 7.338 ops/ms
# Warmup Iteration   3: 7.771 ops/ms
Iteration   1: 7.721 ops/ms
Iteration   2: 7.836 ops/ms
Iteration   3: 7.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.804 ±(99.9%) 1.317 ops/ms [Average]
  (min, avg, max) = (7.721, 7.804, 7.854), stdev = 0.072
  CI (99.9%): [6.487, 9.120] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.003 ms/op
Iteration   1: 3.174 ±(99.9%) 0.003 ms/op
Iteration   2: 3.155 ±(99.9%) 0.002 ms/op
Iteration   3: 3.222 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.184 ±(99.9%) 0.633 ms/op [Average]
  (min, avg, max) = (3.155, 3.184, 3.222), stdev = 0.035
  CI (99.9%): [2.551, 3.817] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.297 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.002 ms/op
Iteration   1: 3.054 ±(99.9%) 0.002 ms/op
Iteration   2: 2.999 ±(99.9%) 0.002 ms/op
Iteration   3: 3.114 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.056 ±(99.9%) 1.043 ms/op [Average]
  (min, avg, max) = (2.999, 3.056, 3.114), stdev = 0.057
  CI (99.9%): [2.013, 4.098] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.361 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.238 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.002 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
Iteration   3: 3.191 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.171 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (3.125, 3.171, 3.198), stdev = 0.040
  CI (99.9%): [2.442, 3.901] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.172 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.010 ms/op
Iteration   1: 4.084 ±(99.9%) 0.013 ms/op
Iteration   2: 4.043 ±(99.9%) 0.015 ms/op
Iteration   3: 3.956 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.028 ±(99.9%) 1.193 ms/op [Average]
  (min, avg, max) = (3.956, 4.028, 4.084), stdev = 0.065
  CI (99.9%): [2.834, 5.221] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.351 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.195 ±(99.9%) 0.008 ms/op
Iteration   1: 3.247 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.166 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 18.327 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   2: 3.245 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.631 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.551 ms/op
                 createUser·p0.9999: 21.702 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   3: 3.210 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.390 ms/op
                 createUser·p0.999:  9.806 ms/op
                 createUser·p0.9999: 26.411 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296713
  mean =      3.234 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21063 
    [ 2.500,  5.000) = 274279 
    [ 5.000,  7.500) = 913 
    [ 7.500, 10.000) = 213 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.137 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      9.507 ms/op
     p(99.9900) =     25.865 ms/op
     p(99.9990) =     26.582 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.170 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.007 ms/op
Iteration   1: 3.117 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.023 ms/op
                 existUser·p0.9999: 17.162 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 3.114 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  5.939 ms/op
                 existUser·p0.9999: 15.310 ms/op
                 existUser·p1.00:   15.860 ms/op

Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.897 ms/op
                 existUser·p0.9999: 18.396 ms/op
                 existUser·p1.00:   19.202 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311455
  mean =      3.083 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1089 
    [ 1.250,  2.500) = 34449 
    [ 2.500,  3.750) = 243191 
    [ 3.750,  5.000) = 31905 
    [ 5.000,  6.250) = 297 
    [ 6.250,  7.500) = 214 
    [ 7.500,  8.750) = 129 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.492 ms/op
     p(99.9900) =     17.072 ms/op
     p(99.9990) =     18.973 ms/op
     p(99.9999) =     19.202 ms/op
    p(100.0000) =     19.202 ms/op


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
# Warmup Iteration   1: 4.471 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.329 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.167 ±(99.9%) 0.007 ms/op
Iteration   1: 3.194 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.088 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.535 ms/op
                 getUser·p0.9999: 23.855 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.658 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  9.319 ms/op
                 getUser·p0.9999: 19.746 ms/op
                 getUser·p1.00:   22.249 ms/op

Iteration   3: 3.246 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.012 ms/op
                 getUser·p0.9999: 23.897 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300688
  mean =      3.192 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20608 
    [ 2.500,  5.000) = 278936 
    [ 5.000,  7.500) = 762 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 83 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.658 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      8.137 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     24.477 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 6.087 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.012 ms/op
Iteration   1: 4.056 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  13.735 ms/op
                 listUser·p0.9999: 16.623 ms/op
                 listUser·p1.00:   16.974 ms/op

Iteration   2: 4.010 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  15.843 ms/op
                 listUser·p0.9999: 18.187 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   3: 3.996 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  21.529 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238737
  mean =      4.021 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2461 
    [ 2.500,  5.000) = 205863 
    [ 5.000,  7.500) = 29011 
    [ 7.500, 10.000) = 962 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     15.590 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     24.429 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.914 ± 3.351  ops/ms
ClientGrpc.existUser                       thrpt       3  10.419 ± 1.548  ops/ms
ClientGrpc.getUser                         thrpt       3  10.020 ± 1.536  ops/ms
ClientGrpc.listUser                        thrpt       3   7.804 ± 1.317  ops/ms
ClientGrpc.createUser                       avgt       3   3.184 ± 0.633   ms/op
ClientGrpc.existUser                        avgt       3   3.056 ± 1.043   ms/op
ClientGrpc.getUser                          avgt       3   3.171 ± 0.730   ms/op
ClientGrpc.listUser                         avgt       3   4.028 ± 1.193   ms/op
ClientGrpc.createUser                     sample  296713   3.234 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.631           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.199           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.953           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.137           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.507           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.865           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.837           ms/op
ClientGrpc.existUser                      sample  311455   3.083 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.718           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.068           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.940           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.492           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.072           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.202           ms/op
ClientGrpc.getUser                        sample  300688   3.192 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.658           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.080           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.137           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.658           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  238737   4.021 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.792           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.743           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.590           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.544           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
