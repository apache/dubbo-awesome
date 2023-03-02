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
# Warmup Iteration   1: 4.646 ops/ms
# Warmup Iteration   2: 9.451 ops/ms
# Warmup Iteration   3: 10.411 ops/ms
Iteration   1: 10.063 ops/ms
Iteration   2: 10.451 ops/ms
Iteration   3: 10.356 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.290 ±(99.9%) 3.689 ops/ms [Average]
  (min, avg, max) = (10.063, 10.290, 10.451), stdev = 0.202
  CI (99.9%): [6.601, 13.980] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.099 ops/ms
# Warmup Iteration   2: 10.676 ops/ms
# Warmup Iteration   3: 10.815 ops/ms
Iteration   1: 10.804 ops/ms
Iteration   2: 10.988 ops/ms
Iteration   3: 10.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.865 ±(99.9%) 1.946 ops/ms [Average]
  (min, avg, max) = (10.802, 10.865, 10.988), stdev = 0.107
  CI (99.9%): [8.919, 12.811] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.326 ops/ms
# Warmup Iteration   2: 10.319 ops/ms
# Warmup Iteration   3: 10.538 ops/ms
Iteration   1: 10.577 ops/ms
Iteration   2: 10.283 ops/ms
Iteration   3: 10.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.450 ±(99.9%) 2.760 ops/ms [Average]
  (min, avg, max) = (10.283, 10.450, 10.577), stdev = 0.151
  CI (99.9%): [7.690, 13.210] (assumes normal distribution)


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
# Warmup Iteration   1: 5.946 ops/ms
# Warmup Iteration   2: 7.841 ops/ms
# Warmup Iteration   3: 7.993 ops/ms
Iteration   1: 8.094 ops/ms
Iteration   2: 8.146 ops/ms
Iteration   3: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.152 ±(99.9%) 1.117 ops/ms [Average]
  (min, avg, max) = (8.094, 8.152, 8.216), stdev = 0.061
  CI (99.9%): [7.035, 9.269] (assumes normal distribution)


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 2.996 ±(99.9%) 0.002 ms/op
Iteration   2: 3.064 ±(99.9%) 0.002 ms/op
Iteration   3: 3.142 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.067 ±(99.9%) 1.328 ms/op [Average]
  (min, avg, max) = (2.996, 3.067, 3.142), stdev = 0.073
  CI (99.9%): [1.739, 4.395] (assumes normal distribution)


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
# Warmup Iteration   1: 3.525 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.004 ms/op
Iteration   1: 2.948 ±(99.9%) 0.002 ms/op
Iteration   2: 2.938 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.950 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.938, 2.950, 2.965), stdev = 0.014
  CI (99.9%): [2.696, 3.205] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.915 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.142 ±(99.9%) 0.003 ms/op
Iteration   1: 3.040 ±(99.9%) 0.002 ms/op
Iteration   2: 3.161 ±(99.9%) 0.006 ms/op
Iteration   3: 3.094 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.098 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (3.040, 3.098, 3.161), stdev = 0.061
  CI (99.9%): [1.994, 4.203] (assumes normal distribution)


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
# Warmup Iteration   1: 5.035 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.017 ms/op
Iteration   1: 4.002 ±(99.9%) 0.011 ms/op
Iteration   2: 3.958 ±(99.9%) 0.014 ms/op
Iteration   3: 3.937 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.966 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (3.937, 3.966, 4.002), stdev = 0.033
  CI (99.9%): [3.363, 4.569] (assumes normal distribution)


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
# Warmup Iteration   1: 3.883 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.642 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  6.957 ms/op
                 createUser·p0.9999: 24.183 ms/op
                 createUser·p1.00:   25.068 ms/op

Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.432 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.801 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  13.339 ms/op
                 createUser·p0.9999: 15.934 ms/op
                 createUser·p1.00:   16.417 ms/op

Iteration   3: 3.143 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.444 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  11.190 ms/op
                 createUser·p0.9999: 23.717 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311868
  mean =      3.079 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24209 
    [ 2.500,  5.000) = 286439 
    [ 5.000,  7.500) = 731 
    [ 7.500, 10.000) = 155 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.432 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =     10.371 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     24.408 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 2.924 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.644 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  5.207 ms/op
                 existUser·p0.9999: 12.241 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   2: 2.939 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.203 ms/op
                 existUser·p0.9999: 14.535 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  5.808 ms/op
                 existUser·p0.9999: 17.912 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 324892
  mean =      2.954 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1898 
    [ 1.250,  2.500) = 48376 
    [ 2.500,  3.750) = 254014 
    [ 3.750,  5.000) = 19749 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 136 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.243 ms/op
     p(99.9900) =     16.739 ms/op
     p(99.9990) =     18.334 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
Iteration   1: 2.964 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.679 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.496 ms/op
                 getUser·p0.9999: 13.592 ms/op
                 getUser·p1.00:   13.976 ms/op

Iteration   2: 3.046 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.342 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  12.027 ms/op
                 getUser·p0.9999: 14.549 ms/op
                 getUser·p1.00:   15.172 ms/op

Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  5.050 ms/op
                 getUser·p0.9999: 13.345 ms/op
                 getUser·p1.00:   15.892 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315417
  mean =      3.042 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2067 
    [ 1.250,  2.500) = 22884 
    [ 2.500,  3.750) = 270486 
    [ 3.750,  5.000) = 18774 
    [ 5.000,  6.250) = 624 
    [ 6.250,  7.500) = 244 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 126 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.342 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      7.725 ms/op
     p(99.9900) =     13.597 ms/op
     p(99.9990) =     15.101 ms/op
     p(99.9999) =     15.892 ms/op
    p(100.0000) =     15.892 ms/op


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
# Warmup Iteration   1: 5.032 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.010 ms/op
Iteration   1: 3.911 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.480 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 16.525 ms/op
                 listUser·p1.00:   17.105 ms/op

Iteration   2: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.285 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  12.782 ms/op
                 listUser·p0.9999: 15.535 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.866 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  20.575 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244339
  mean =      3.929 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5780 
    [ 2.500,  5.000) = 209447 
    [ 5.000,  7.500) = 27924 
    [ 7.500, 10.000) = 801 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      5.112 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     13.244 ms/op
     p(99.9900) =     23.757 ms/op
     p(99.9990) =     25.020 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.290 ± 3.689  ops/ms
ClientGrpc.existUser                       thrpt       3  10.865 ± 1.946  ops/ms
ClientGrpc.getUser                         thrpt       3  10.450 ± 2.760  ops/ms
ClientGrpc.listUser                        thrpt       3   8.152 ± 1.117  ops/ms
ClientGrpc.createUser                       avgt       3   3.067 ± 1.328   ms/op
ClientGrpc.existUser                        avgt       3   2.950 ± 0.254   ms/op
ClientGrpc.getUser                          avgt       3   3.098 ± 1.105   ms/op
ClientGrpc.listUser                         avgt       3   3.966 ± 0.603   ms/op
ClientGrpc.createUser                     sample  311868   3.079 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.432           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.052           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.686           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.371           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.626           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.068           ms/op
ClientGrpc.existUser                      sample  324892   2.954 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.644           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.243           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.739           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.448           ms/op
ClientGrpc.getUser                        sample  315417   3.042 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.342           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.725           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.597           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.892           ms/op
ClientGrpc.listUser                       sample  244339   3.929 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.285           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.112           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.244           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.757           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.035           ms/op
