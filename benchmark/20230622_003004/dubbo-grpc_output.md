# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.240 ops/ms
# Warmup Iteration   2: 9.140 ops/ms
# Warmup Iteration   3: 9.823 ops/ms
Iteration   1: 10.423 ops/ms
Iteration   2: 10.214 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.461 ±(99.9%) 4.881 ops/ms [Average]
  (min, avg, max) = (10.214, 10.461, 10.745), stdev = 0.268
  CI (99.9%): [5.580, 15.342] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.788 ops/ms
# Warmup Iteration   2: 10.422 ops/ms
# Warmup Iteration   3: 10.921 ops/ms
Iteration   1: 11.150 ops/ms
Iteration   2: 11.008 ops/ms
Iteration   3: 10.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.046 ±(99.9%) 1.666 ops/ms [Average]
  (min, avg, max) = (10.979, 11.046, 11.150), stdev = 0.091
  CI (99.9%): [9.379, 12.712] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.943 ops/ms
# Warmup Iteration   2: 10.020 ops/ms
# Warmup Iteration   3: 10.456 ops/ms
Iteration   1: 10.493 ops/ms
Iteration   2: 10.485 ops/ms
Iteration   3: 10.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.458 ±(99.9%) 1.004 ops/ms [Average]
  (min, avg, max) = (10.394, 10.458, 10.493), stdev = 0.055
  CI (99.9%): [9.454, 11.461] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.350 ops/ms
# Warmup Iteration   2: 7.834 ops/ms
# Warmup Iteration   3: 8.204 ops/ms
Iteration   1: 8.270 ops/ms
Iteration   2: 8.130 ops/ms
Iteration   3: 8.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.168 ±(99.9%) 1.619 ops/ms [Average]
  (min, avg, max) = (8.105, 8.168, 8.270), stdev = 0.089
  CI (99.9%): [6.549, 9.787] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.356 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.004 ms/op
Iteration   1: 3.123 ±(99.9%) 0.004 ms/op
Iteration   2: 3.176 ±(99.9%) 0.002 ms/op
Iteration   3: 3.137 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.145 ±(99.9%) 0.497 ms/op [Average]
  (min, avg, max) = (3.123, 3.145, 3.176), stdev = 0.027
  CI (99.9%): [2.648, 3.642] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.227 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.979 ±(99.9%) 0.003 ms/op
Iteration   1: 2.932 ±(99.9%) 0.003 ms/op
Iteration   2: 3.005 ±(99.9%) 0.001 ms/op
Iteration   3: 2.990 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.975 ±(99.9%) 0.705 ms/op [Average]
  (min, avg, max) = (2.932, 2.975, 3.005), stdev = 0.039
  CI (99.9%): [2.271, 3.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.322 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.005 ms/op
Iteration   1: 3.047 ±(99.9%) 0.004 ms/op
Iteration   2: 3.074 ±(99.9%) 0.003 ms/op
Iteration   3: 3.033 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.051 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (3.033, 3.051, 3.074), stdev = 0.021
  CI (99.9%): [2.669, 3.434] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.585 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.951 ±(99.9%) 0.016 ms/op
Iteration   1: 3.983 ±(99.9%) 0.018 ms/op
Iteration   2: 4.031 ±(99.9%) 0.017 ms/op
Iteration   3: 4.006 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.007 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (3.983, 4.007, 4.031), stdev = 0.024
  CI (99.9%): [3.568, 4.445] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.312 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.079 ±(99.9%) 0.006 ms/op
Iteration   1: 3.090 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  9.330 ms/op
                 createUser·p0.9999: 15.575 ms/op
                 createUser·p1.00:   16.466 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.781 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.621 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.750 ms/op
                 createUser·p0.9999: 16.389 ms/op
                 createUser·p1.00:   17.531 ms/op

Iteration   3: 3.040 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.551 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  8.094 ms/op
                 createUser·p0.9999: 19.545 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315706
  mean =      3.039 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1000 
    [ 1.250,  2.500) = 20115 
    [ 2.500,  3.750) = 276711 
    [ 3.750,  5.000) = 15875 
    [ 5.000,  6.250) = 1033 
    [ 6.250,  7.500) = 500 
    [ 7.500,  8.750) = 185 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 55 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.724 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      8.546 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     19.628 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.038 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.005 ms/op
Iteration   1: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  6.638 ms/op
                 existUser·p0.9999: 18.622 ms/op
                 existUser·p1.00:   19.300 ms/op

Iteration   2: 2.919 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  6.270 ms/op
                 existUser·p0.9999: 13.387 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 2.930 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.797 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.047 ms/op
                 existUser·p0.999:  6.536 ms/op
                 existUser·p0.9999: 16.238 ms/op
                 existUser·p1.00:   16.597 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327294
  mean =      2.932 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 561 
    [ 1.250,  2.500) = 26981 
    [ 2.500,  3.750) = 291556 
    [ 3.750,  5.000) = 7119 
    [ 5.000,  6.250) = 673 
    [ 6.250,  7.500) = 167 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      6.453 ms/op
     p(99.9900) =     16.929 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.197 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.007 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  8.652 ms/op
                 getUser·p0.9999: 16.328 ms/op
                 getUser·p1.00:   16.761 ms/op

Iteration   2: 3.012 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.889 ms/op
                 getUser·p0.9999: 14.670 ms/op
                 getUser·p1.00:   14.975 ms/op

Iteration   3: 3.024 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.391 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   4.106 ms/op
                 getUser·p0.999:  6.619 ms/op
                 getUser·p0.9999: 18.771 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316384
  mean =      3.032 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 533 
    [ 1.250,  2.500) = 17017 
    [ 2.500,  3.750) = 284830 
    [ 3.750,  5.000) = 12600 
    [ 5.000,  6.250) = 892 
    [ 6.250,  7.500) = 213 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.353 ms/op
     p(99.9900) =     17.485 ms/op
     p(99.9990) =     18.967 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.508 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.078 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.010 ms/op
Iteration   1: 3.935 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.827 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 22.138 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   2: 3.981 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.542 ms/op
                 listUser·p0.9999: 18.905 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   3: 3.919 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  15.093 ms/op
                 listUser·p0.9999: 24.790 ms/op
                 listUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243279
  mean =      3.945 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3942 
    [ 2.500,  5.000) = 215455 
    [ 5.000,  7.500) = 22499 
    [ 7.500, 10.000) = 947 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.876 ms/op
     p(99.9900) =     24.270 ms/op
     p(99.9990) =     25.021 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.461 ± 4.881  ops/ms
ClientGrpc.existUser                       thrpt       3  11.046 ± 1.666  ops/ms
ClientGrpc.getUser                         thrpt       3  10.458 ± 1.004  ops/ms
ClientGrpc.listUser                        thrpt       3   8.168 ± 1.619  ops/ms
ClientGrpc.createUser                       avgt       3   3.145 ± 0.497   ms/op
ClientGrpc.existUser                        avgt       3   2.975 ± 0.705   ms/op
ClientGrpc.getUser                          avgt       3   3.051 ± 0.382   ms/op
ClientGrpc.listUser                         avgt       3   4.007 ± 0.439   ms/op
ClientGrpc.createUser                     sample  315706   3.039 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.724           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.011           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.546           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.235           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.726           ms/op
ClientGrpc.existUser                      sample  327294   2.932 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.598           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.453           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.929           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.300           ms/op
ClientGrpc.getUser                        sample  316384   3.032 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.763           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.353           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.485           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.104           ms/op
ClientGrpc.listUser                       sample  243279   3.945 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.827           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.876           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.270           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.199           ms/op
