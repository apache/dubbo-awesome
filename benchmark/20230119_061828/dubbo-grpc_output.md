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
# Warmup Iteration   1: 4.901 ops/ms
# Warmup Iteration   2: 9.551 ops/ms
# Warmup Iteration   3: 10.163 ops/ms
Iteration   1: 10.380 ops/ms
Iteration   2: 10.189 ops/ms
Iteration   3: 10.095 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.221 ±(99.9%) 2.650 ops/ms [Average]
  (min, avg, max) = (10.095, 10.221, 10.380), stdev = 0.145
  CI (99.9%): [7.571, 12.871] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.117 ops/ms
# Warmup Iteration   2: 10.764 ops/ms
# Warmup Iteration   3: 10.775 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.917 ops/ms
Iteration   3: 11.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.878 ±(99.9%) 3.064 ops/ms [Average]
  (min, avg, max) = (10.695, 10.878, 11.024), stdev = 0.168
  CI (99.9%): [7.814, 13.943] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.812 ops/ms
# Warmup Iteration   2: 10.535 ops/ms
# Warmup Iteration   3: 10.333 ops/ms
Iteration   1: 10.354 ops/ms
Iteration   2: 10.730 ops/ms
Iteration   3: 10.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.525 ±(99.9%) 3.477 ops/ms [Average]
  (min, avg, max) = (10.354, 10.525, 10.730), stdev = 0.191
  CI (99.9%): [7.048, 14.001] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.932 ops/ms
# Warmup Iteration   2: 8.042 ops/ms
# Warmup Iteration   3: 8.036 ops/ms
Iteration   1: 7.913 ops/ms
Iteration   2: 8.149 ops/ms
Iteration   3: 8.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.109 ±(99.9%) 3.276 ops/ms [Average]
  (min, avg, max) = (7.913, 8.109, 8.266), stdev = 0.180
  CI (99.9%): [4.834, 11.385] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.002 ms/op
Iteration   1: 2.982 ±(99.9%) 0.002 ms/op
Iteration   2: 2.978 ±(99.9%) 0.003 ms/op
Iteration   3: 3.096 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.019 ±(99.9%) 1.214 ms/op [Average]
  (min, avg, max) = (2.978, 3.019, 3.096), stdev = 0.067
  CI (99.9%): [1.805, 4.233] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.888 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.002 ms/op
Iteration   1: 3.008 ±(99.9%) 0.002 ms/op
Iteration   2: 2.915 ±(99.9%) 0.002 ms/op
Iteration   3: 3.001 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.975 ±(99.9%) 0.953 ms/op [Average]
  (min, avg, max) = (2.915, 2.975, 3.008), stdev = 0.052
  CI (99.9%): [2.022, 3.928] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.918 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.079 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.002 ms/op
Iteration   1: 2.957 ±(99.9%) 0.002 ms/op
Iteration   2: 3.060 ±(99.9%) 0.001 ms/op
Iteration   3: 3.022 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.013 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (2.957, 3.013, 3.060), stdev = 0.052
  CI (99.9%): [2.064, 3.962] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.444 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.980 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.824 ±(99.9%) 0.008 ms/op
Iteration   1: 3.851 ±(99.9%) 0.050 ms/op
Iteration   2: 3.922 ±(99.9%) 0.019 ms/op
Iteration   3: 3.943 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.905 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (3.851, 3.905, 3.943), stdev = 0.048
  CI (99.9%): [3.023, 4.787] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.059 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.008 ms/op
Iteration   1: 3.072 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.142 ms/op
                 createUser·p0.9999: 15.378 ms/op
                 createUser·p1.00:   15.794 ms/op

Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.705 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.697 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.895 ms/op
                 createUser·p0.9999: 24.301 ms/op
                 createUser·p1.00:   27.132 ms/op

Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.682 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  9.716 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312025
  mean =      3.076 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31877 
    [ 2.500,  5.000) = 279261 
    [ 5.000,  7.500) = 531 
    [ 7.500, 10.000) = 156 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.888 ms/op
     p(99.9900) =     19.916 ms/op
     p(99.9990) =     25.810 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.986 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
Iteration   1: 2.969 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.639 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.204 ms/op
                 existUser·p0.9999: 11.968 ms/op
                 existUser·p1.00:   12.255 ms/op

Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  5.445 ms/op
                 existUser·p0.9999: 13.828 ms/op
                 existUser·p1.00:   13.976 ms/op

Iteration   3: 2.922 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  6.234 ms/op
                 existUser·p0.9999: 27.264 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326051
  mean =      2.944 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53326 
    [ 2.500,  5.000) = 272131 
    [ 5.000,  7.500) = 367 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.149 ms/op
     p(99.9000) =      6.324 ms/op
     p(99.9900) =     19.989 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 3.985 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.103 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.170 ms/op
                 getUser·p0.9999: 11.977 ms/op
                 getUser·p1.00:   12.173 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.182 ms/op
                 getUser·p0.999:  7.217 ms/op
                 getUser·p0.9999: 13.143 ms/op
                 getUser·p1.00:   14.565 ms/op

Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.420 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.255 ms/op
                 getUser·p0.9999: 25.199 ms/op
                 getUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317701
  mean =      3.022 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34966 
    [ 2.500,  5.000) = 281527 
    [ 5.000,  7.500) = 932 
    [ 7.500, 10.000) = 66 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.217 ms/op
     p(99.9900) =     24.616 ms/op
     p(99.9990) =     25.384 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 4.426 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.972 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.011 ms/op
Iteration   1: 3.824 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  12.190 ms/op
                 listUser·p0.9999: 17.945 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   2: 3.948 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.843 ms/op
                 listUser·p0.999:  13.351 ms/op
                 listUser·p0.9999: 25.487 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   3: 3.922 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.256 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  15.339 ms/op
                 listUser·p0.9999: 21.164 ms/op
                 listUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246082
  mean =      3.897 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4827 
    [ 2.500,  5.000) = 216950 
    [ 5.000,  7.500) = 23211 
    [ 7.500, 10.000) = 638 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.256 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.989 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.451 ms/op
     p(99.9900) =     22.177 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.221 ± 2.650  ops/ms
ClientGrpc.existUser                       thrpt       3  10.878 ± 3.064  ops/ms
ClientGrpc.getUser                         thrpt       3  10.525 ± 3.477  ops/ms
ClientGrpc.listUser                        thrpt       3   8.109 ± 3.276  ops/ms
ClientGrpc.createUser                       avgt       3   3.019 ± 1.214   ms/op
ClientGrpc.existUser                        avgt       3   2.975 ± 0.953   ms/op
ClientGrpc.getUser                          avgt       3   3.013 ± 0.949   ms/op
ClientGrpc.listUser                         avgt       3   3.905 ± 0.882   ms/op
ClientGrpc.createUser                     sample  312025   3.076 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.682           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.888           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.916           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.132           ms/op
ClientGrpc.existUser                      sample  326051   2.944 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.639           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.925           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.149           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.324           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.989           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.525           ms/op
ClientGrpc.getUser                        sample  317701   3.022 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.420           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.019           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.217           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.616           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.494           ms/op
ClientGrpc.listUser                       sample  246082   3.897 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.256           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.989           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.742           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.451           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.177           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.788           ms/op
