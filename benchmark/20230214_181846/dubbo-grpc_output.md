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
# Warmup Iteration   1: 4.349 ops/ms
# Warmup Iteration   2: 9.228 ops/ms
# Warmup Iteration   3: 9.776 ops/ms
Iteration   1: 9.926 ops/ms
Iteration   2: 9.915 ops/ms
Iteration   3: 10.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.992 ±(99.9%) 2.252 ops/ms [Average]
  (min, avg, max) = (9.915, 9.992, 10.134), stdev = 0.123
  CI (99.9%): [7.740, 12.244] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 7.628 ops/ms
# Warmup Iteration   2: 10.308 ops/ms
# Warmup Iteration   3: 10.606 ops/ms
Iteration   1: 10.528 ops/ms
Iteration   2: 10.499 ops/ms
Iteration   3: 10.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.564 ±(99.9%) 1.625 ops/ms [Average]
  (min, avg, max) = (10.499, 10.564, 10.666), stdev = 0.089
  CI (99.9%): [8.940, 12.189] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.639 ops/ms
# Warmup Iteration   2: 10.022 ops/ms
# Warmup Iteration   3: 10.012 ops/ms
Iteration   1: 10.112 ops/ms
Iteration   2: 9.884 ops/ms
Iteration   3: 10.281 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.092 ±(99.9%) 3.636 ops/ms [Average]
  (min, avg, max) = (9.884, 10.092, 10.281), stdev = 0.199
  CI (99.9%): [6.456, 13.729] (assumes normal distribution)


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
# Warmup Iteration   1: 5.303 ops/ms
# Warmup Iteration   2: 7.555 ops/ms
# Warmup Iteration   3: 7.833 ops/ms
Iteration   1: 7.940 ops/ms
Iteration   2: 7.908 ops/ms
Iteration   3: 8.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.963 ±(99.9%) 1.279 ops/ms [Average]
  (min, avg, max) = (7.908, 7.963, 8.042), stdev = 0.070
  CI (99.9%): [6.684, 9.242] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.128 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.010 ms/op
Iteration   1: 3.074 ±(99.9%) 0.004 ms/op
Iteration   2: 3.245 ±(99.9%) 0.002 ms/op
Iteration   3: 3.131 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.150 ±(99.9%) 1.591 ms/op [Average]
  (min, avg, max) = (3.074, 3.150, 3.245), stdev = 0.087
  CI (99.9%): [1.559, 4.741] (assumes normal distribution)


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
# Warmup Iteration   1: 3.964 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.002 ms/op
Iteration   2: 3.044 ±(99.9%) 0.002 ms/op
Iteration   3: 3.010 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.031 ±(99.9%) 0.328 ms/op [Average]
  (min, avg, max) = (3.010, 3.031, 3.044), stdev = 0.018
  CI (99.9%): [2.703, 3.359] (assumes normal distribution)


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
# Warmup Iteration   1: 3.934 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.184 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.171 ±(99.9%) 0.003 ms/op
Iteration   1: 3.146 ±(99.9%) 0.002 ms/op
Iteration   2: 3.189 ±(99.9%) 0.002 ms/op
Iteration   3: 3.137 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.157 ±(99.9%) 0.506 ms/op [Average]
  (min, avg, max) = (3.137, 3.157, 3.189), stdev = 0.028
  CI (99.9%): [2.651, 3.664] (assumes normal distribution)


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
# Warmup Iteration   1: 5.136 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.174 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.006 ms/op
Iteration   1: 4.055 ±(99.9%) 0.052 ms/op
Iteration   2: 4.008 ±(99.9%) 0.062 ms/op
Iteration   3: 4.052 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.038 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (4.008, 4.038, 4.055), stdev = 0.027
  CI (99.9%): [3.553, 4.524] (assumes normal distribution)


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
# Warmup Iteration   1: 4.353 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
Iteration   1: 3.206 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.883 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  7.334 ms/op
                 createUser·p0.9999: 20.317 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 3.117 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  7.847 ms/op
                 createUser·p0.9999: 19.053 ms/op
                 createUser·p1.00:   19.530 ms/op

Iteration   3: 3.010 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.067 ms/op
                 createUser·p0.999:  7.248 ms/op
                 createUser·p0.9999: 26.051 ms/op
                 createUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308848
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31972 
    [ 2.500,  5.000) = 276011 
    [ 5.000,  7.500) = 558 
    [ 7.500, 10.000) = 56 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.489 ms/op
     p(99.9900) =     24.210 ms/op
     p(99.9990) =     26.405 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 3.854 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.006 ms/op
Iteration   1: 2.953 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.986 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   3.990 ms/op
                 existUser·p0.999:  6.666 ms/op
                 existUser·p0.9999: 13.227 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   2: 2.903 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.777 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.125 ms/op
                 existUser·p0.999:  7.290 ms/op
                 existUser·p0.9999: 14.024 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.821 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  7.811 ms/op
                 existUser·p0.9999: 15.881 ms/op
                 existUser·p1.00:   16.761 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331948
  mean =      2.892 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2010 
    [ 1.250,  2.500) = 67766 
    [ 2.500,  3.750) = 247140 
    [ 3.750,  5.000) = 14257 
    [ 5.000,  6.250) = 263 
    [ 6.250,  7.500) = 251 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.051 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     15.267 ms/op
     p(99.9990) =     16.623 ms/op
     p(99.9999) =     16.761 ms/op
    p(100.0000) =     16.761 ms/op


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
# Warmup Iteration   1: 4.015 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.006 ms/op
Iteration   1: 3.034 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.752 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.067 ms/op
                 getUser·p0.9999: 16.490 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 2.991 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.737 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.645 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  6.579 ms/op
                 getUser·p0.9999: 16.496 ms/op
                 getUser·p1.00:   18.055 ms/op

Iteration   3: 2.963 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 19.838 ms/op
                 getUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320221
  mean =      2.996 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42875 
    [ 2.500,  5.000) = 276094 
    [ 5.000,  7.500) = 956 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.737 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.264 ms/op
     p(99.9900) =     18.121 ms/op
     p(99.9990) =     20.303 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 5.200 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.012 ms/op
Iteration   1: 3.813 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  14.270 ms/op
                 listUser·p0.9999: 17.564 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.741 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.947 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 26.968 ms/op
                 listUser·p1.00:   29.229 ms/op

Iteration   3: 3.871 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.833 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.374 ms/op
                 listUser·p0.9999: 17.686 ms/op
                 listUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252200
  mean =      3.807 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6816 
    [ 2.500,  5.000) = 221443 
    [ 5.000,  7.500) = 22723 
    [ 7.500, 10.000) = 690 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.713 ms/op
     p(99.9900) =     26.317 ms/op
     p(99.9990) =     28.638 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.992 ± 2.252  ops/ms
ClientGrpc.existUser                       thrpt       3  10.564 ± 1.625  ops/ms
ClientGrpc.getUser                         thrpt       3  10.092 ± 3.636  ops/ms
ClientGrpc.listUser                        thrpt       3   7.963 ± 1.279  ops/ms
ClientGrpc.createUser                       avgt       3   3.150 ± 1.591   ms/op
ClientGrpc.existUser                        avgt       3   3.031 ± 0.328   ms/op
ClientGrpc.getUser                          avgt       3   3.157 ± 0.506   ms/op
ClientGrpc.listUser                         avgt       3   4.038 ± 0.485   ms/op
ClientGrpc.createUser                     sample  308848   3.109 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.539           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.252           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.489           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.210           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.509           ms/op
ClientGrpc.existUser                      sample  331948   2.892 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.640           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.051           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.102           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.267           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.761           ms/op
ClientGrpc.getUser                        sample  320221   2.996 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.737           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.970           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.781           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.264           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.121           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.414           ms/op
ClientGrpc.listUser                       sample  252200   3.807 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.947           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.713           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.317           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.229           ms/op
