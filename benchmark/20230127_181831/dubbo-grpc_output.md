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
# Warmup Iteration   1: 3.923 ops/ms
# Warmup Iteration   2: 8.695 ops/ms
# Warmup Iteration   3: 9.932 ops/ms
Iteration   1: 10.113 ops/ms
Iteration   2: 9.912 ops/ms
Iteration   3: 10.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.013 ±(99.9%) 1.831 ops/ms [Average]
  (min, avg, max) = (9.912, 10.013, 10.113), stdev = 0.100
  CI (99.9%): [8.183, 11.844] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.492 ops/ms
# Warmup Iteration   2: 10.071 ops/ms
# Warmup Iteration   3: 10.256 ops/ms
Iteration   1: 10.329 ops/ms
Iteration   2: 10.562 ops/ms
Iteration   3: 10.461 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.451 ±(99.9%) 2.128 ops/ms [Average]
  (min, avg, max) = (10.329, 10.451, 10.562), stdev = 0.117
  CI (99.9%): [8.322, 12.579] (assumes normal distribution)


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
# Warmup Iteration   1: 6.642 ops/ms
# Warmup Iteration   2: 9.972 ops/ms
# Warmup Iteration   3: 10.053 ops/ms
Iteration   1: 9.928 ops/ms
Iteration   2: 9.916 ops/ms
Iteration   3: 9.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.927 ±(99.9%) 0.178 ops/ms [Average]
  (min, avg, max) = (9.916, 9.927, 9.936), stdev = 0.010
  CI (99.9%): [9.748, 10.105] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.262 ops/ms
# Warmup Iteration   2: 7.482 ops/ms
# Warmup Iteration   3: 7.831 ops/ms
Iteration   1: 7.860 ops/ms
Iteration   2: 7.902 ops/ms
Iteration   3: 7.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.890 ±(99.9%) 0.469 ops/ms [Average]
  (min, avg, max) = (7.860, 7.890, 7.906), stdev = 0.026
  CI (99.9%): [7.421, 8.358] (assumes normal distribution)


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
# Warmup Iteration   1: 4.227 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.003 ms/op
Iteration   1: 3.261 ±(99.9%) 0.006 ms/op
Iteration   2: 3.253 ±(99.9%) 0.002 ms/op
Iteration   3: 3.296 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.270 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.253, 3.270, 3.296), stdev = 0.022
  CI (99.9%): [2.860, 3.680] (assumes normal distribution)


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
# Warmup Iteration   1: 4.097 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.002 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
Iteration   2: 3.092 ±(99.9%) 0.002 ms/op
Iteration   3: 3.082 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.081 ±(99.9%) 0.213 ms/op [Average]
  (min, avg, max) = (3.069, 3.081, 3.092), stdev = 0.012
  CI (99.9%): [2.868, 3.294] (assumes normal distribution)


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
# Warmup Iteration   1: 4.378 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.233 ±(99.9%) 0.002 ms/op
Iteration   1: 3.170 ±(99.9%) 0.003 ms/op
Iteration   2: 3.220 ±(99.9%) 0.002 ms/op
Iteration   3: 3.196 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.195 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (3.170, 3.195, 3.220), stdev = 0.025
  CI (99.9%): [2.735, 3.656] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.283 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.195 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.013 ms/op
Iteration   1: 4.050 ±(99.9%) 0.006 ms/op
Iteration   2: 3.996 ±(99.9%) 0.005 ms/op
Iteration   3: 4.099 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.048 ±(99.9%) 0.944 ms/op [Average]
  (min, avg, max) = (3.996, 4.048, 4.099), stdev = 0.052
  CI (99.9%): [3.105, 4.992] (assumes normal distribution)


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
# Warmup Iteration   1: 4.480 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.006 ms/op
Iteration   1: 3.199 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  6.881 ms/op
                 createUser·p0.9999: 13.484 ms/op
                 createUser·p1.00:   13.992 ms/op

Iteration   2: 3.179 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.310 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.822 ms/op
                 createUser·p0.95:   3.977 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.037 ms/op
                 createUser·p0.9999: 14.778 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   3: 3.279 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  8.935 ms/op
                 createUser·p0.9999: 26.845 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 298104
  mean =      3.219 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16739 
    [ 2.500,  5.000) = 280406 
    [ 5.000,  7.500) = 671 
    [ 7.500, 10.000) = 96 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.310 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     26.968 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 4.023 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.006 ms/op
Iteration   1: 3.082 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   3.113 ms/op
                 existUser·p0.90:   3.846 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  6.209 ms/op
                 existUser·p0.9999: 13.296 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 3.114 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.063 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  6.849 ms/op
                 existUser·p0.9999: 14.729 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   3: 2.972 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.923 ms/op
                 existUser·p0.9999: 17.833 ms/op
                 existUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314358
  mean =      3.055 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2159 
    [ 1.250,  2.500) = 40063 
    [ 2.500,  3.750) = 235941 
    [ 3.750,  5.000) = 35513 
    [ 5.000,  6.250) = 307 
    [ 6.250,  7.500) = 166 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.840 ms/op
     p(99.9900) =     16.073 ms/op
     p(99.9990) =     18.144 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 4.530 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.322 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.007 ms/op
Iteration   1: 3.235 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.953 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   4.514 ms/op
                 getUser·p0.999:  6.568 ms/op
                 getUser·p0.9999: 13.732 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 3.259 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.413 ms/op
                 getUser·p0.9999: 14.451 ms/op
                 getUser·p1.00:   14.991 ms/op

Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.006 ms/op
                 getUser·p0.9999: 28.217 ms/op
                 getUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 295800
  mean =      3.243 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17283 
    [ 2.500,  5.000) = 277448 
    [ 5.000,  7.500) = 838 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.104 ms/op
     p(99.9900) =     26.195 ms/op
     p(99.9990) =     28.475 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 5.840 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.114 ±(99.9%) 0.012 ms/op
Iteration   1: 4.052 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  17.270 ms/op
                 listUser·p0.9999: 25.788 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   2: 4.105 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  14.651 ms/op
                 listUser·p0.9999: 27.506 ms/op
                 listUser·p1.00:   27.984 ms/op

Iteration   3: 4.053 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.874 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  15.466 ms/op
                 listUser·p0.9999: 18.605 ms/op
                 listUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235751
  mean =      4.070 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2282 
    [ 2.500,  5.000) = 206533 
    [ 5.000,  7.500) = 25519 
    [ 7.500, 10.000) = 913 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     16.474 ms/op
     p(99.9900) =     25.821 ms/op
     p(99.9990) =     27.818 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.013 ± 1.831  ops/ms
ClientGrpc.existUser                       thrpt       3  10.451 ± 2.128  ops/ms
ClientGrpc.getUser                         thrpt       3   9.927 ± 0.178  ops/ms
ClientGrpc.listUser                        thrpt       3   7.890 ± 0.469  ops/ms
ClientGrpc.createUser                       avgt       3   3.270 ± 0.410   ms/op
ClientGrpc.existUser                        avgt       3   3.081 ± 0.213   ms/op
ClientGrpc.getUser                          avgt       3   3.195 ± 0.460   ms/op
ClientGrpc.listUser                         avgt       3   4.048 ± 0.944   ms/op
ClientGrpc.createUser                     sample  298104   3.219 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.310           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.187           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.080           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.406           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.313           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  314358   3.055 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.560           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.060           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.977           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.840           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.073           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.285           ms/op
ClientGrpc.getUser                        sample  295800   3.243 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.808           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.219           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.129           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.104           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.195           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.508           ms/op
ClientGrpc.listUser                       sample  235751   4.070 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.964           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.891           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.474           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.821           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.984           ms/op
