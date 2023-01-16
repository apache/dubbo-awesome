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
# Warmup Iteration   1: 4.235 ops/ms
# Warmup Iteration   2: 8.906 ops/ms
# Warmup Iteration   3: 10.227 ops/ms
Iteration   1: 10.364 ops/ms
Iteration   2: 10.223 ops/ms
Iteration   3: 10.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.249 ±(99.9%) 1.914 ops/ms [Average]
  (min, avg, max) = (10.159, 10.249, 10.364), stdev = 0.105
  CI (99.9%): [8.335, 12.163] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.885 ops/ms
# Warmup Iteration   2: 10.694 ops/ms
# Warmup Iteration   3: 10.814 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.874 ops/ms
Iteration   3: 10.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.855 ±(99.9%) 2.760 ops/ms [Average]
  (min, avg, max) = (10.695, 10.855, 10.995), stdev = 0.151
  CI (99.9%): [8.094, 13.615] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.374 ops/ms
# Warmup Iteration   2: 10.324 ops/ms
# Warmup Iteration   3: 10.510 ops/ms
Iteration   1: 10.534 ops/ms
Iteration   2: 10.409 ops/ms
Iteration   3: 10.421 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.455 ±(99.9%) 1.250 ops/ms [Average]
  (min, avg, max) = (10.409, 10.455, 10.534), stdev = 0.069
  CI (99.9%): [9.205, 11.705] (assumes normal distribution)


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
# Warmup Iteration   1: 6.558 ops/ms
# Warmup Iteration   2: 7.494 ops/ms
# Warmup Iteration   3: 7.910 ops/ms
Iteration   1: 7.941 ops/ms
Iteration   2: 7.760 ops/ms
Iteration   3: 8.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.974 ±(99.9%) 4.238 ops/ms [Average]
  (min, avg, max) = (7.760, 7.974, 8.221), stdev = 0.232
  CI (99.9%): [3.736, 12.212] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.170 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.004 ms/op
Iteration   1: 3.136 ±(99.9%) 0.003 ms/op
Iteration   2: 3.076 ±(99.9%) 0.002 ms/op
Iteration   3: 3.122 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.111 ±(99.9%) 0.571 ms/op [Average]
  (min, avg, max) = (3.076, 3.111, 3.136), stdev = 0.031
  CI (99.9%): [2.540, 3.682] (assumes normal distribution)


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.983 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.001 ms/op
Iteration   2: 3.029 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.007 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (2.965, 3.007, 3.029), stdev = 0.036
  CI (99.9%): [2.349, 3.664] (assumes normal distribution)


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
# Warmup Iteration   1: 3.827 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.002 ±(99.9%) 0.005 ms/op
Iteration   1: 3.092 ±(99.9%) 0.002 ms/op
Iteration   2: 3.027 ±(99.9%) 0.002 ms/op
Iteration   3: 3.078 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.027, 3.066, 3.092), stdev = 0.034
  CI (99.9%): [2.444, 3.688] (assumes normal distribution)


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
# Warmup Iteration   1: 4.315 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.010 ms/op
Iteration   1: 3.999 ±(99.9%) 0.020 ms/op
Iteration   2: 4.054 ±(99.9%) 0.015 ms/op
Iteration   3: 3.823 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.958 ±(99.9%) 2.201 ms/op [Average]
  (min, avg, max) = (3.823, 3.958, 4.054), stdev = 0.121
  CI (99.9%): [1.757, 6.160] (assumes normal distribution)


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.005 ms/op
Iteration   1: 3.092 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.751 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.072 ms/op
                 createUser·p0.9999: 12.004 ms/op
                 createUser·p1.00:   12.452 ms/op

Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.659 ms/op
                 createUser·p0.9999: 13.238 ms/op
                 createUser·p1.00:   13.631 ms/op

Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.690 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.349 ms/op
                 createUser·p0.9999: 15.820 ms/op
                 createUser·p1.00:   16.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311745
  mean =      3.079 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1292 
    [ 1.250,  2.500) = 24017 
    [ 2.500,  3.750) = 262737 
    [ 3.750,  5.000) = 22592 
    [ 5.000,  6.250) = 477 
    [ 6.250,  7.500) = 299 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 22 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.690 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.621 ms/op
     p(99.9900) =     15.499 ms/op
     p(99.9990) =     16.294 ms/op
     p(99.9999) =     16.433 ms/op
    p(100.0000) =     16.433 ms/op


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
# Warmup Iteration   1: 3.869 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.006 ms/op
Iteration   1: 2.999 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  6.046 ms/op
                 existUser·p0.9999: 18.525 ms/op
                 existUser·p1.00:   18.711 ms/op

Iteration   2: 2.976 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.186 ms/op
                 existUser·p0.999:  5.633 ms/op
                 existUser·p0.9999: 17.122 ms/op
                 existUser·p1.00:   17.531 ms/op

Iteration   3: 2.920 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  7.440 ms/op
                 existUser·p0.9999: 14.975 ms/op
                 existUser·p1.00:   15.385 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323757
  mean =      2.965 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2780 
    [ 1.250,  2.500) = 48889 
    [ 2.500,  3.750) = 249121 
    [ 3.750,  5.000) = 22259 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 92 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 44 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      6.267 ms/op
     p(99.9900) =     17.858 ms/op
     p(99.9990) =     18.612 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 3.887 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.111 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.977 ms/op
                 getUser·p0.9999: 19.053 ms/op
                 getUser·p1.00:   19.399 ms/op

Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.473 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.145 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   17.007 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.639 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.846 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  5.918 ms/op
                 getUser·p0.9999: 13.338 ms/op
                 getUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312147
  mean =      3.074 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1555 
    [ 1.250,  2.500) = 21626 
    [ 2.500,  3.750) = 264525 
    [ 3.750,  5.000) = 23418 
    [ 5.000,  6.250) = 552 
    [ 6.250,  7.500) = 204 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.473 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.895 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.930 ms/op
     p(99.9900) =     18.158 ms/op
     p(99.9990) =     19.325 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.253 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.961 ±(99.9%) 0.010 ms/op
Iteration   1: 4.027 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.151 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.183 ms/op
                 listUser·p0.9999: 20.580 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   2: 4.121 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.962 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   7.172 ms/op
                 listUser·p0.999:  16.586 ms/op
                 listUser·p0.9999: 20.742 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 4.036 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  20.808 ms/op
                 listUser·p0.9999: 26.935 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236287
  mean =      4.061 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3268 
    [ 2.500,  5.000) = 198248 
    [ 5.000,  7.500) = 33502 
    [ 7.500, 10.000) = 888 
    [10.000, 12.500) = 52 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      5.235 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.964 ms/op
     p(99.9000) =     15.746 ms/op
     p(99.9900) =     26.378 ms/op
     p(99.9990) =     27.159 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.249 ± 1.914  ops/ms
ClientGrpc.existUser                       thrpt       3  10.855 ± 2.760  ops/ms
ClientGrpc.getUser                         thrpt       3  10.455 ± 1.250  ops/ms
ClientGrpc.listUser                        thrpt       3   7.974 ± 4.238  ops/ms
ClientGrpc.createUser                       avgt       3   3.111 ± 0.571   ms/op
ClientGrpc.existUser                        avgt       3   3.007 ± 0.658   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.622   ms/op
ClientGrpc.listUser                         avgt       3   3.958 ± 2.201   ms/op
ClientGrpc.createUser                     sample  311745   3.079 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.690           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.621           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.499           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.433           ms/op
ClientGrpc.existUser                      sample  323757   2.965 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.660           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.654           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.838           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.267           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.858           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.711           ms/op
ClientGrpc.getUser                        sample  312147   3.074 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.473           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.895           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.930           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.158           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.399           ms/op
ClientGrpc.listUser                       sample  236287   4.061 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.962           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.964           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.746           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.378           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
