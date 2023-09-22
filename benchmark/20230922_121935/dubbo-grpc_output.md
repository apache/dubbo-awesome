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
# Warmup Iteration   1: 3.911 ops/ms
# Warmup Iteration   2: 8.493 ops/ms
# Warmup Iteration   3: 9.761 ops/ms
Iteration   1: 9.956 ops/ms
Iteration   2: 10.398 ops/ms
Iteration   3: 10.427 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.260 ±(99.9%) 4.818 ops/ms [Average]
  (min, avg, max) = (9.956, 10.260, 10.427), stdev = 0.264
  CI (99.9%): [5.442, 15.078] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.379 ops/ms
# Warmup Iteration   2: 10.270 ops/ms
# Warmup Iteration   3: 10.722 ops/ms
Iteration   1: 10.796 ops/ms
Iteration   2: 10.697 ops/ms
Iteration   3: 10.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.755 ±(99.9%) 0.943 ops/ms [Average]
  (min, avg, max) = (10.697, 10.755, 10.796), stdev = 0.052
  CI (99.9%): [9.812, 11.698] (assumes normal distribution)


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
# Warmup Iteration   1: 6.220 ops/ms
# Warmup Iteration   2: 9.793 ops/ms
# Warmup Iteration   3: 10.050 ops/ms
Iteration   1: 10.214 ops/ms
Iteration   2: 10.333 ops/ms
Iteration   3: 10.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.247 ±(99.9%) 1.365 ops/ms [Average]
  (min, avg, max) = (10.194, 10.247, 10.333), stdev = 0.075
  CI (99.9%): [8.882, 11.612] (assumes normal distribution)


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
# Warmup Iteration   1: 5.197 ops/ms
# Warmup Iteration   2: 7.915 ops/ms
# Warmup Iteration   3: 7.937 ops/ms
Iteration   1: 8.031 ops/ms
Iteration   2: 8.054 ops/ms
Iteration   3: 8.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.090 ±(99.9%) 1.502 ops/ms [Average]
  (min, avg, max) = (8.031, 8.090, 8.184), stdev = 0.082
  CI (99.9%): [6.588, 9.592] (assumes normal distribution)


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
# Warmup Iteration   1: 4.360 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.002 ms/op
Iteration   1: 3.158 ±(99.9%) 0.002 ms/op
Iteration   2: 3.190 ±(99.9%) 0.001 ms/op
Iteration   3: 3.166 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.171 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.158, 3.171, 3.190), stdev = 0.017
  CI (99.9%): [2.870, 3.473] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.001 ms/op
Iteration   1: 3.085 ±(99.9%) 0.001 ms/op
Iteration   2: 3.043 ±(99.9%) 0.002 ms/op
Iteration   3: 3.050 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.059 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (3.043, 3.059, 3.085), stdev = 0.022
  CI (99.9%): [2.650, 3.468] (assumes normal distribution)


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
# Warmup Iteration   1: 4.218 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.001 ms/op
Iteration   1: 3.123 ±(99.9%) 0.002 ms/op
Iteration   2: 3.150 ±(99.9%) 0.002 ms/op
Iteration   3: 3.122 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.131 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (3.122, 3.131, 3.150), stdev = 0.016
  CI (99.9%): [2.841, 3.422] (assumes normal distribution)


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
# Warmup Iteration   1: 5.526 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.005 ±(99.9%) 0.020 ms/op
Iteration   1: 3.962 ±(99.9%) 0.010 ms/op
Iteration   2: 3.913 ±(99.9%) 0.034 ms/op
Iteration   3: 3.931 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.935 ±(99.9%) 0.452 ms/op [Average]
  (min, avg, max) = (3.913, 3.935, 3.962), stdev = 0.025
  CI (99.9%): [3.483, 4.387] (assumes normal distribution)


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
# Warmup Iteration   1: 4.541 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.327 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.250 ±(99.9%) 0.008 ms/op
Iteration   1: 3.111 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  7.456 ms/op
                 createUser·p0.9999: 19.905 ms/op
                 createUser·p1.00:   21.070 ms/op

Iteration   2: 3.094 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.636 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  7.501 ms/op
                 createUser·p0.9999: 19.616 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.870 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  8.639 ms/op
                 createUser·p0.9999: 21.983 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307505
  mean =      3.120 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8645 
    [ 2.500,  5.000) = 297190 
    [ 5.000,  7.500) = 1337 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      7.807 ms/op
     p(99.9900) =     20.857 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 3.951 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.005 ms/op
Iteration   1: 3.004 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  7.865 ms/op
                 existUser·p0.9999: 13.173 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   2: 3.016 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.267 ms/op
                 existUser·p0.999:  9.584 ms/op
                 existUser·p0.9999: 13.989 ms/op
                 existUser·p1.00:   15.352 ms/op

Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.513 ms/op
                 existUser·p0.9999: 16.253 ms/op
                 existUser·p1.00:   16.450 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318640
  mean =      3.013 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 970 
    [ 1.250,  2.500) = 21469 
    [ 2.500,  3.750) = 278729 
    [ 3.750,  5.000) = 16045 
    [ 5.000,  6.250) = 785 
    [ 6.250,  7.500) = 296 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 62 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.758 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     14.746 ms/op
     p(99.9990) =     16.368 ms/op
     p(99.9999) =     16.450 ms/op
    p(100.0000) =     16.450 ms/op


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
# Warmup Iteration   1: 4.431 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.007 ms/op
Iteration   1: 3.198 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  8.681 ms/op
                 getUser·p0.9999: 14.008 ms/op
                 getUser·p1.00:   14.352 ms/op

Iteration   2: 3.170 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  10.535 ms/op
                 getUser·p0.9999: 14.626 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   3: 3.169 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.626 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.325 ms/op
                 getUser·p0.9999: 17.276 ms/op
                 getUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302127
  mean =      3.179 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 263 
    [ 1.250,  2.500) = 6118 
    [ 2.500,  3.750) = 268487 
    [ 3.750,  5.000) = 25446 
    [ 5.000,  6.250) = 1031 
    [ 6.250,  7.500) = 361 
    [ 7.500,  8.750) = 140 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     17.725 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 5.529 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.008 ms/op
Iteration   1: 3.963 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.890 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.587 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   2: 4.018 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.783 ms/op
                 listUser·p0.9999: 16.045 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 3.897 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.476 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  13.682 ms/op
                 listUser·p0.9999: 18.153 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242599
  mean =      3.959 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 12 
    [ 1.250,  2.500) = 1856 
    [ 2.500,  3.750) = 88124 
    [ 3.750,  5.000) = 138792 
    [ 5.000,  6.250) = 8555 
    [ 6.250,  7.500) = 4310 
    [ 7.500,  8.750) = 365 
    [ 8.750, 10.000) = 172 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 133 
    [13.750, 15.000) = 96 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 52 

  Percentiles, ms/op:
      p(0.0000) =      0.476 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     13.697 ms/op
     p(99.9900) =     18.145 ms/op
     p(99.9990) =     18.697 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.260 ± 4.818  ops/ms
ClientGrpc.existUser                       thrpt       3  10.755 ± 0.943  ops/ms
ClientGrpc.getUser                         thrpt       3  10.247 ± 1.365  ops/ms
ClientGrpc.listUser                        thrpt       3   8.090 ± 1.502  ops/ms
ClientGrpc.createUser                       avgt       3   3.171 ± 0.301   ms/op
ClientGrpc.existUser                        avgt       3   3.059 ± 0.409   ms/op
ClientGrpc.getUser                          avgt       3   3.131 ± 0.291   ms/op
ClientGrpc.listUser                         avgt       3   3.935 ± 0.452   ms/op
ClientGrpc.createUser                     sample  307505   3.120 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.636           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.807           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.857           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  318640   3.013 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.758           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.276           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.815           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.746           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.450           ms/op
ClientGrpc.getUser                        sample  302127   3.179 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.626           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.719           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.924           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.925           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.891           ms/op
ClientGrpc.listUser                       sample  242599   3.959 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.476           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.424           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.697           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.145           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.743           ms/op
