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
# Warmup Iteration   1: 4.785 ops/ms
# Warmup Iteration   2: 8.760 ops/ms
# Warmup Iteration   3: 10.148 ops/ms
Iteration   1: 10.559 ops/ms
Iteration   2: 10.355 ops/ms
Iteration   3: 10.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.425 ±(99.9%) 2.121 ops/ms [Average]
  (min, avg, max) = (10.355, 10.425, 10.559), stdev = 0.116
  CI (99.9%): [8.303, 12.546] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.001 ops/ms
# Warmup Iteration   2: 10.845 ops/ms
# Warmup Iteration   3: 10.887 ops/ms
Iteration   1: 10.816 ops/ms
Iteration   2: 10.934 ops/ms
Iteration   3: 10.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.870 ±(99.9%) 1.083 ops/ms [Average]
  (min, avg, max) = (10.816, 10.870, 10.934), stdev = 0.059
  CI (99.9%): [9.788, 11.953] (assumes normal distribution)


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
# Warmup Iteration   1: 8.294 ops/ms
# Warmup Iteration   2: 10.190 ops/ms
# Warmup Iteration   3: 10.332 ops/ms
Iteration   1: 10.441 ops/ms
Iteration   2: 10.395 ops/ms
Iteration   3: 10.335 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.390 ±(99.9%) 0.967 ops/ms [Average]
  (min, avg, max) = (10.335, 10.390, 10.441), stdev = 0.053
  CI (99.9%): [9.423, 11.357] (assumes normal distribution)


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
# Warmup Iteration   1: 7.174 ops/ms
# Warmup Iteration   2: 7.681 ops/ms
# Warmup Iteration   3: 7.833 ops/ms
Iteration   1: 7.820 ops/ms
Iteration   2: 8.151 ops/ms
Iteration   3: 8.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.019 ±(99.9%) 3.208 ops/ms [Average]
  (min, avg, max) = (7.820, 8.019, 8.151), stdev = 0.176
  CI (99.9%): [4.812, 11.227] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.116 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.010 ms/op
Iteration   1: 3.128 ±(99.9%) 0.002 ms/op
Iteration   2: 3.029 ±(99.9%) 0.002 ms/op
Iteration   3: 3.046 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.068 ±(99.9%) 0.960 ms/op [Average]
  (min, avg, max) = (3.029, 3.068, 3.128), stdev = 0.053
  CI (99.9%): [2.108, 4.027] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.940 ±(99.9%) 0.003 ms/op
Iteration   1: 2.985 ±(99.9%) 0.002 ms/op
Iteration   2: 2.897 ±(99.9%) 0.002 ms/op
Iteration   3: 2.977 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.953 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (2.897, 2.953, 2.985), stdev = 0.048
  CI (99.9%): [2.069, 3.837] (assumes normal distribution)


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
# Warmup Iteration   1: 4.040 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.157 ±(99.9%) 0.002 ms/op
Iteration   1: 3.063 ±(99.9%) 0.003 ms/op
Iteration   2: 2.995 ±(99.9%) 0.002 ms/op
Iteration   3: 3.000 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.019 ±(99.9%) 0.690 ms/op [Average]
  (min, avg, max) = (2.995, 3.019, 3.063), stdev = 0.038
  CI (99.9%): [2.329, 3.710] (assumes normal distribution)


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
# Warmup Iteration   1: 4.393 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.985 ±(99.9%) 0.018 ms/op
Iteration   1: 3.953 ±(99.9%) 0.010 ms/op
Iteration   2: 3.938 ±(99.9%) 0.050 ms/op
Iteration   3: 3.959 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.950 ±(99.9%) 0.193 ms/op [Average]
  (min, avg, max) = (3.938, 3.950, 3.959), stdev = 0.011
  CI (99.9%): [3.758, 4.143] (assumes normal distribution)


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
# Warmup Iteration   1: 3.935 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
Iteration   1: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.726 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.593 ms/op
                 createUser·p0.9999: 12.042 ms/op
                 createUser·p1.00:   12.452 ms/op

Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.737 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.660 ms/op
                 createUser·p0.9999: 20.213 ms/op
                 createUser·p1.00:   20.611 ms/op

Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  10.564 ms/op
                 createUser·p0.9999: 15.140 ms/op
                 createUser·p1.00:   16.171 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308271
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28819 
    [ 2.500,  5.000) = 278360 
    [ 5.000,  7.500) = 645 
    [ 7.500, 10.000) = 205 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.634 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     19.634 ms/op
     p(99.9990) =     20.510 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 3.682 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.984 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.006 ms/op
Iteration   1: 2.965 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.440 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  10.027 ms/op
                 existUser·p0.9999: 16.460 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   2: 2.956 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.654 ms/op
                 existUser·p0.9999: 22.419 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.141 ms/op
                 existUser·p0.9999: 18.598 ms/op
                 existUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323230
  mean =      2.970 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42487 
    [ 2.500,  5.000) = 280000 
    [ 5.000,  7.500) = 419 
    [ 7.500, 10.000) = 87 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.440 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.523 ms/op
     p(99.9900) =     20.835 ms/op
     p(99.9990) =     22.668 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.006 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.936 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  8.241 ms/op
                 getUser·p0.9999: 20.087 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.795 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  11.182 ms/op
                 getUser·p0.9999: 12.841 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   3: 3.092 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.432 ms/op
                 getUser·p0.9999: 15.307 ms/op
                 getUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309105
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24115 
    [ 2.500,  5.000) = 284146 
    [ 5.000,  7.500) = 489 
    [ 7.500, 10.000) = 108 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.728 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.198 ms/op
     p(99.9900) =     19.470 ms/op
     p(99.9990) =     20.248 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.231 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.003 ±(99.9%) 0.011 ms/op
Iteration   1: 4.046 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  11.813 ms/op
                 listUser·p0.9999: 13.558 ms/op
                 listUser·p1.00:   15.106 ms/op

Iteration   2: 4.087 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.784 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  18.724 ms/op
                 listUser·p0.9999: 22.288 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   3: 4.060 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  17.506 ms/op
                 listUser·p0.9999: 22.720 ms/op
                 listUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236236
  mean =      4.064 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3908 
    [ 2.500,  5.000) = 202681 
    [ 5.000,  7.500) = 28151 
    [ 7.500, 10.000) = 1009 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.210 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.521 ms/op
     p(99.9900) =     22.413 ms/op
     p(99.9990) =     23.927 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.425 ± 2.121  ops/ms
ClientGrpc.existUser                       thrpt       3  10.870 ± 1.083  ops/ms
ClientGrpc.getUser                         thrpt       3  10.390 ± 0.967  ops/ms
ClientGrpc.listUser                        thrpt       3   8.019 ± 3.208  ops/ms
ClientGrpc.createUser                       avgt       3   3.068 ± 0.960   ms/op
ClientGrpc.existUser                        avgt       3   2.953 ± 0.884   ms/op
ClientGrpc.getUser                          avgt       3   3.019 ± 0.690   ms/op
ClientGrpc.listUser                         avgt       3   3.950 ± 0.193   ms/op
ClientGrpc.createUser                     sample  308271   3.113 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.634           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.618           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.634           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.611           ms/op
ClientGrpc.existUser                      sample  323230   2.970 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.440           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.957           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.523           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.835           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.708           ms/op
ClientGrpc.getUser                        sample  309105   3.107 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.728           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.772           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.198           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.470           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.349           ms/op
ClientGrpc.listUser                       sample  236236   4.064 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.892           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.210           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.521           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.413           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.805           ms/op
