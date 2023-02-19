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
# Warmup Iteration   1: 4.182 ops/ms
# Warmup Iteration   2: 9.121 ops/ms
# Warmup Iteration   3: 10.064 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.394 ops/ms
Iteration   3: 10.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.285 ±(99.9%) 4.494 ops/ms [Average]
  (min, avg, max) = (10.003, 10.285, 10.459), stdev = 0.246
  CI (99.9%): [5.791, 14.780] (assumes normal distribution)


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
# Warmup Iteration   1: 7.882 ops/ms
# Warmup Iteration   2: 10.636 ops/ms
# Warmup Iteration   3: 10.676 ops/ms
Iteration   1: 10.770 ops/ms
Iteration   2: 11.199 ops/ms
Iteration   3: 10.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.862 ±(99.9%) 5.500 ops/ms [Average]
  (min, avg, max) = (10.618, 10.862, 11.199), stdev = 0.301
  CI (99.9%): [5.362, 16.362] (assumes normal distribution)


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
# Warmup Iteration   1: 7.227 ops/ms
# Warmup Iteration   2: 10.084 ops/ms
# Warmup Iteration   3: 10.302 ops/ms
Iteration   1: 10.443 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 10.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.368 ±(99.9%) 1.298 ops/ms [Average]
  (min, avg, max) = (10.302, 10.368, 10.443), stdev = 0.071
  CI (99.9%): [9.070, 11.665] (assumes normal distribution)


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
# Warmup Iteration   1: 5.388 ops/ms
# Warmup Iteration   2: 7.745 ops/ms
# Warmup Iteration   3: 7.984 ops/ms
Iteration   1: 8.190 ops/ms
Iteration   2: 7.900 ops/ms
Iteration   3: 8.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.044 ±(99.9%) 2.644 ops/ms [Average]
  (min, avg, max) = (7.900, 8.044, 8.190), stdev = 0.145
  CI (99.9%): [5.400, 10.688] (assumes normal distribution)


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
# Warmup Iteration   1: 4.134 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.003 ms/op
Iteration   1: 3.094 ±(99.9%) 0.004 ms/op
Iteration   2: 3.120 ±(99.9%) 0.002 ms/op
Iteration   3: 3.125 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.113 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (3.094, 3.113, 3.125), stdev = 0.016
  CI (99.9%): [2.814, 3.412] (assumes normal distribution)


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
# Warmup Iteration   1: 4.150 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.002 ms/op
Iteration   1: 2.932 ±(99.9%) 0.002 ms/op
Iteration   2: 2.812 ±(99.9%) 0.002 ms/op
Iteration   3: 2.978 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.907 ±(99.9%) 1.560 ms/op [Average]
  (min, avg, max) = (2.812, 2.907, 2.978), stdev = 0.085
  CI (99.9%): [1.348, 4.467] (assumes normal distribution)


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
# Warmup Iteration   1: 4.193 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.150 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.003 ms/op
Iteration   1: 3.043 ±(99.9%) 0.003 ms/op
Iteration   2: 3.092 ±(99.9%) 0.006 ms/op
Iteration   3: 3.120 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.085 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (3.043, 3.085, 3.120), stdev = 0.039
  CI (99.9%): [2.371, 3.799] (assumes normal distribution)


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
# Warmup Iteration   1: 5.554 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.118 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.016 ms/op
Iteration   1: 3.981 ±(99.9%) 0.015 ms/op
Iteration   2: 3.988 ±(99.9%) 0.027 ms/op
Iteration   3: 3.765 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.911 ±(99.9%) 2.313 ms/op [Average]
  (min, avg, max) = (3.765, 3.911, 3.988), stdev = 0.127
  CI (99.9%): [1.598, 6.224] (assumes normal distribution)


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
# Warmup Iteration   1: 4.275 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.730 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.429 ms/op
                 createUser·p0.9999: 12.511 ms/op
                 createUser·p1.00:   12.829 ms/op

Iteration   2: 3.172 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.852 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.863 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  10.324 ms/op
                 createUser·p0.9999: 13.827 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   3: 3.145 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  15.958 ms/op
                 createUser·p0.9999: 21.627 ms/op
                 createUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306637
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28967 
    [ 2.500,  5.000) = 276490 
    [ 5.000,  7.500) = 730 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      9.967 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     23.755 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


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
# Warmup Iteration   1: 4.146 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.829 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.793 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  5.997 ms/op
                 existUser·p0.9999: 12.976 ms/op
                 existUser·p1.00:   13.255 ms/op

Iteration   2: 2.977 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  7.366 ms/op
                 existUser·p0.9999: 14.180 ms/op
                 existUser·p1.00:   14.483 ms/op

Iteration   3: 3.075 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.285 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  9.212 ms/op
                 existUser·p0.9999: 19.063 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318365
  mean =      3.018 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40828 
    [ 2.500,  5.000) = 276689 
    [ 5.000,  7.500) = 582 
    [ 7.500, 10.000) = 85 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.285 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      6.974 ms/op
     p(99.9900) =     18.022 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 4.437 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.008 ms/op
Iteration   1: 3.152 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.777 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 13.327 ms/op
                 getUser·p1.00:   13.828 ms/op

Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.798 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  6.280 ms/op
                 getUser·p0.9999: 14.316 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 3.106 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.780 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  5.988 ms/op
                 getUser·p0.9999: 24.153 ms/op
                 getUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308983
  mean =      3.106 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28885 
    [ 2.500,  5.000) = 279166 
    [ 5.000,  7.500) = 702 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.780 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.545 ms/op
     p(99.9900) =     22.551 ms/op
     p(99.9990) =     24.832 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 5.024 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.178 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.011 ms/op
Iteration   1: 3.976 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.680 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  13.764 ms/op
                 listUser·p0.9999: 19.102 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 3.985 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 25.198 ms/op
                 listUser·p1.00:   25.559 ms/op

Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 22.769 ms/op
                 listUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242002
  mean =      3.965 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1492 
    [ 2.500,  5.000) = 220036 
    [ 5.000,  7.500) = 19281 
    [ 7.500, 10.000) = 725 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.505 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     24.196 ms/op
     p(99.9990) =     25.471 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.285 ± 4.494  ops/ms
ClientGrpc.existUser                       thrpt       3  10.862 ± 5.500  ops/ms
ClientGrpc.getUser                         thrpt       3  10.368 ± 1.298  ops/ms
ClientGrpc.listUser                        thrpt       3   8.044 ± 2.644  ops/ms
ClientGrpc.createUser                       avgt       3   3.113 ± 0.299   ms/op
ClientGrpc.existUser                        avgt       3   2.907 ± 1.560   ms/op
ClientGrpc.getUser                          avgt       3   3.085 ± 0.714   ms/op
ClientGrpc.listUser                         avgt       3   3.911 ± 2.313   ms/op
ClientGrpc.createUser                     sample  306637   3.129 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.730           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.399           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.967           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.087           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.855           ms/op
ClientGrpc.existUser                      sample  318365   3.018 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.285           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.637           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.805           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.974           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.022           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.525           ms/op
ClientGrpc.getUser                        sample  308983   3.106 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.780           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.545           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.551           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.199           ms/op
ClientGrpc.listUser                       sample  242002   3.965 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.680           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.817           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.505           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.734           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.499           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.196           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.559           ms/op
