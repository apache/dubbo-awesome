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
# Warmup Iteration   1: 4.111 ops/ms
# Warmup Iteration   2: 9.238 ops/ms
# Warmup Iteration   3: 10.032 ops/ms
Iteration   1: 10.137 ops/ms
Iteration   2: 10.439 ops/ms
Iteration   3: 10.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.200 ±(99.9%) 3.913 ops/ms [Average]
  (min, avg, max) = (10.025, 10.200, 10.439), stdev = 0.214
  CI (99.9%): [6.287, 14.114] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.999 ops/ms
# Warmup Iteration   2: 10.294 ops/ms
# Warmup Iteration   3: 10.295 ops/ms
Iteration   1: 10.580 ops/ms
Iteration   2: 10.837 ops/ms
Iteration   3: 10.774 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.730 ±(99.9%) 2.444 ops/ms [Average]
  (min, avg, max) = (10.580, 10.730, 10.837), stdev = 0.134
  CI (99.9%): [8.287, 13.174] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.855 ops/ms
# Warmup Iteration   2: 9.712 ops/ms
# Warmup Iteration   3: 9.930 ops/ms
Iteration   1: 10.323 ops/ms
Iteration   2: 10.179 ops/ms
Iteration   3: 10.140 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.214 ±(99.9%) 1.758 ops/ms [Average]
  (min, avg, max) = (10.140, 10.214, 10.323), stdev = 0.096
  CI (99.9%): [8.456, 11.972] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.086 ops/ms
# Warmup Iteration   2: 7.639 ops/ms
# Warmup Iteration   3: 7.822 ops/ms
Iteration   1: 7.995 ops/ms
Iteration   2: 7.825 ops/ms
Iteration   3: 7.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.929 ±(99.9%) 1.664 ops/ms [Average]
  (min, avg, max) = (7.825, 7.929, 7.995), stdev = 0.091
  CI (99.9%): [6.265, 9.593] (assumes normal distribution)


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
# Warmup Iteration   1: 4.308 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.002 ms/op
Iteration   1: 3.188 ±(99.9%) 0.011 ms/op
Iteration   2: 3.229 ±(99.9%) 0.002 ms/op
Iteration   3: 3.235 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.217 ±(99.9%) 0.474 ms/op [Average]
  (min, avg, max) = (3.188, 3.217, 3.235), stdev = 0.026
  CI (99.9%): [2.743, 3.692] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.072 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.002 ms/op
Iteration   1: 3.110 ±(99.9%) 0.002 ms/op
Iteration   2: 3.082 ±(99.9%) 0.002 ms/op
Iteration   3: 3.109 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.100 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (3.082, 3.100, 3.110), stdev = 0.016
  CI (99.9%): [2.805, 3.396] (assumes normal distribution)


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
# Warmup Iteration   1: 4.043 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.277 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.002 ms/op
Iteration   1: 3.183 ±(99.9%) 0.002 ms/op
Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
Iteration   3: 3.111 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.146 ±(99.9%) 0.657 ms/op [Average]
  (min, avg, max) = (3.111, 3.146, 3.183), stdev = 0.036
  CI (99.9%): [2.489, 3.803] (assumes normal distribution)


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
# Warmup Iteration   1: 6.258 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.149 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.103 ±(99.9%) 0.014 ms/op
Iteration   1: 4.070 ±(99.9%) 0.013 ms/op
Iteration   2: 4.037 ±(99.9%) 0.021 ms/op
Iteration   3: 4.021 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.043 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (4.021, 4.043, 4.070), stdev = 0.025
  CI (99.9%): [3.584, 4.501] (assumes normal distribution)


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
# Warmup Iteration   1: 4.482 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
Iteration   1: 3.245 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.072 ms/op
                 createUser·p0.9999: 18.228 ms/op
                 createUser·p1.00:   18.711 ms/op

Iteration   2: 3.197 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.813 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  8.118 ms/op
                 createUser·p0.9999: 33.095 ms/op
                 createUser·p1.00:   33.554 ms/op

Iteration   3: 3.188 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.709 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  9.307 ms/op
                 createUser·p0.9999: 26.639 ms/op
                 createUser·p1.00:   28.017 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 299186
  mean =      3.210 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22452 
    [ 2.500,  5.000) = 275786 
    [ 5.000,  7.500) = 547 
    [ 7.500, 10.000) = 176 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.709 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      8.546 ms/op
     p(99.9900) =     32.416 ms/op
     p(99.9990) =     33.489 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 3.966 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
Iteration   1: 3.107 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.939 ms/op
                 existUser·p0.9999: 14.223 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   2: 2.993 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.004 ms/op
                 existUser·p0.9999: 14.334 ms/op
                 existUser·p1.00:   14.795 ms/op

Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  8.788 ms/op
                 existUser·p0.9999: 17.552 ms/op
                 existUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313586
  mean =      3.061 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1863 
    [ 1.250,  2.500) = 36638 
    [ 2.500,  3.750) = 244684 
    [ 3.750,  5.000) = 29450 
    [ 5.000,  6.250) = 471 
    [ 6.250,  7.500) = 160 
    [ 7.500,  8.750) = 101 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.285 ms/op
     p(99.9000) =      7.602 ms/op
     p(99.9900) =     16.678 ms/op
     p(99.9990) =     18.240 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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
# Warmup Iteration   1: 4.273 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
Iteration   1: 3.161 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  7.400 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   22.446 ms/op

Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  8.411 ms/op
                 getUser·p0.9999: 24.248 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   3: 3.116 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  7.457 ms/op
                 getUser·p0.9999: 25.625 ms/op
                 getUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306282
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25845 
    [ 2.500,  5.000) = 279260 
    [ 5.000,  7.500) = 840 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.868 ms/op
     p(99.9900) =     25.395 ms/op
     p(99.9990) =     26.519 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 5.227 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.137 ±(99.9%) 0.011 ms/op
Iteration   1: 4.018 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.992 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  15.024 ms/op
                 listUser·p0.9999: 20.285 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 3.943 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.037 ms/op
                 listUser·p0.9999: 18.043 ms/op
                 listUser·p1.00:   18.514 ms/op

Iteration   3: 3.982 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.856 ms/op
                 listUser·p0.999:  15.712 ms/op
                 listUser·p0.9999: 20.871 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241206
  mean =      3.981 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1632 
    [ 2.500,  5.000) = 217893 
    [ 5.000,  7.500) = 20592 
    [ 7.500, 10.000) = 628 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.992 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.603 ms/op
     p(99.0000) =      6.840 ms/op
     p(99.9000) =     15.037 ms/op
     p(99.9900) =     20.283 ms/op
     p(99.9990) =     22.300 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.200 ± 3.913  ops/ms
ClientGrpc.existUser                       thrpt       3  10.730 ± 2.444  ops/ms
ClientGrpc.getUser                         thrpt       3  10.214 ± 1.758  ops/ms
ClientGrpc.listUser                        thrpt       3   7.929 ± 1.664  ops/ms
ClientGrpc.createUser                       avgt       3   3.217 ± 0.474   ms/op
ClientGrpc.existUser                        avgt       3   3.100 ± 0.295   ms/op
ClientGrpc.getUser                          avgt       3   3.146 ± 0.657   ms/op
ClientGrpc.listUser                         avgt       3   4.043 ± 0.459   ms/op
ClientGrpc.createUser                     sample  299186   3.210 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.709           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.183           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.546           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          32.416           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.554           ms/op
ClientGrpc.existUser                      sample  313586   3.061 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.800           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.056           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.740           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.920           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.285           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.602           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.678           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.842           ms/op
ClientGrpc.getUser                        sample  306282   3.134 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.754           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.105           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.973           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.868           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.395           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.706           ms/op
ClientGrpc.listUser                       sample  241206   3.981 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.992           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.603           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.037           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.283           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
