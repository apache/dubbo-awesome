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
# Warmup Iteration   1: 3.821 ops/ms
# Warmup Iteration   2: 8.681 ops/ms
# Warmup Iteration   3: 9.726 ops/ms
Iteration   1: 9.949 ops/ms
Iteration   2: 9.785 ops/ms
Iteration   3: 10.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.964 ±(99.9%) 3.409 ops/ms [Average]
  (min, avg, max) = (9.785, 9.964, 10.158), stdev = 0.187
  CI (99.9%): [6.554, 13.373] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.187 ops/ms
# Warmup Iteration   2: 10.119 ops/ms
# Warmup Iteration   3: 10.221 ops/ms
Iteration   1: 10.481 ops/ms
Iteration   2: 10.312 ops/ms
Iteration   3: 10.208 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.333 ±(99.9%) 2.522 ops/ms [Average]
  (min, avg, max) = (10.208, 10.333, 10.481), stdev = 0.138
  CI (99.9%): [7.812, 12.855] (assumes normal distribution)


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
# Warmup Iteration   1: 6.405 ops/ms
# Warmup Iteration   2: 9.543 ops/ms
# Warmup Iteration   3: 9.863 ops/ms
Iteration   1: 9.975 ops/ms
Iteration   2: 9.998 ops/ms
Iteration   3: 10.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.002 ±(99.9%) 0.548 ops/ms [Average]
  (min, avg, max) = (9.975, 10.002, 10.034), stdev = 0.030
  CI (99.9%): [9.455, 10.550] (assumes normal distribution)


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
# Warmup Iteration   1: 4.805 ops/ms
# Warmup Iteration   2: 7.496 ops/ms
# Warmup Iteration   3: 7.636 ops/ms
Iteration   1: 7.716 ops/ms
Iteration   2: 7.610 ops/ms
Iteration   3: 7.996 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.774 ±(99.9%) 3.638 ops/ms [Average]
  (min, avg, max) = (7.610, 7.774, 7.996), stdev = 0.199
  CI (99.9%): [4.137, 11.412] (assumes normal distribution)


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
# Warmup Iteration   1: 4.539 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.002 ms/op
Iteration   1: 3.286 ±(99.9%) 0.002 ms/op
Iteration   2: 3.339 ±(99.9%) 0.002 ms/op
Iteration   3: 3.327 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.317 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.286, 3.317, 3.339), stdev = 0.028
  CI (99.9%): [2.804, 3.830] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.979 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.002 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.010 ±(99.9%) 0.002 ms/op
Iteration   3: 3.139 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.099 ±(99.9%) 1.408 ms/op [Average]
  (min, avg, max) = (3.010, 3.099, 3.147), stdev = 0.077
  CI (99.9%): [1.691, 4.507] (assumes normal distribution)


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
# Warmup Iteration   1: 4.577 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.138 ±(99.9%) 0.003 ms/op
Iteration   1: 3.171 ±(99.9%) 0.002 ms/op
Iteration   2: 3.233 ±(99.9%) 0.002 ms/op
Iteration   3: 3.222 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.209 ±(99.9%) 0.601 ms/op [Average]
  (min, avg, max) = (3.171, 3.209, 3.233), stdev = 0.033
  CI (99.9%): [2.607, 3.810] (assumes normal distribution)


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
# Warmup Iteration   1: 5.710 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.330 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.215 ±(99.9%) 0.010 ms/op
Iteration   1: 4.134 ±(99.9%) 0.005 ms/op
Iteration   2: 4.098 ±(99.9%) 0.007 ms/op
Iteration   3: 4.115 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.115 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (4.098, 4.115, 4.134), stdev = 0.018
  CI (99.9%): [3.787, 4.444] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.310 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
Iteration   1: 3.163 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  7.790 ms/op
                 createUser·p0.9999: 13.005 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.395 ms/op
                 createUser·p0.9999: 14.385 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   3: 3.205 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.664 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  10.050 ms/op
                 createUser·p0.9999: 18.089 ms/op
                 createUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303223
  mean =      3.166 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 428 
    [ 1.250,  2.500) = 21918 
    [ 2.500,  3.750) = 242524 
    [ 3.750,  5.000) = 37023 
    [ 5.000,  6.250) = 685 
    [ 6.250,  7.500) = 289 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 63 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.664 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.215 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     18.479 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 3.895 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.007 ms/op
Iteration   1: 3.242 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   3.232 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  8.168 ms/op
                 existUser·p0.9999: 15.604 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  8.793 ms/op
                 existUser·p0.9999: 21.508 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   3: 3.129 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  10.624 ms/op
                 existUser·p0.9999: 17.287 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 303926
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25787 
    [ 2.500,  5.000) = 277158 
    [ 5.000,  7.500) = 582 
    [ 7.500, 10.000) = 122 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.022 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      9.376 ms/op
     p(99.9900) =     19.759 ms/op
     p(99.9990) =     21.982 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 4.511 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.007 ms/op
Iteration   1: 3.228 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.012 ms/op
                 getUser·p0.50:   3.199 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  7.118 ms/op
                 getUser·p0.9999: 18.548 ms/op
                 getUser·p1.00:   19.661 ms/op

Iteration   2: 3.181 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.080 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.435 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   3: 3.164 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.861 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.808 ms/op
                 getUser·p0.9999: 16.042 ms/op
                 getUser·p1.00:   17.302 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300728
  mean =      3.191 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 282 
    [ 1.250,  2.500) = 20321 
    [ 2.500,  3.750) = 237017 
    [ 3.750,  5.000) = 41798 
    [ 5.000,  6.250) = 641 
    [ 6.250,  7.500) = 355 
    [ 7.500,  8.750) = 124 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.861 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.588 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     19.332 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 5.656 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.079 ±(99.9%) 0.011 ms/op
Iteration   1: 4.103 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.098 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.154 ms/op
                 listUser·p0.999:  14.730 ms/op
                 listUser·p0.9999: 16.322 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 4.038 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.280 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 4.019 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.358 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.510 ms/op
                 listUser·p0.9999: 27.725 ms/op
                 listUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236790
  mean =      4.053 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1622 
    [ 2.500,  5.000) = 210031 
    [ 5.000,  7.500) = 23853 
    [ 7.500, 10.000) = 780 
    [10.000, 12.500) = 111 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.996 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     26.094 ms/op
     p(99.9990) =     28.156 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.964 ± 3.409  ops/ms
ClientGrpc.existUser                       thrpt       3  10.333 ± 2.522  ops/ms
ClientGrpc.getUser                         thrpt       3  10.002 ± 0.548  ops/ms
ClientGrpc.listUser                        thrpt       3   7.774 ± 3.638  ops/ms
ClientGrpc.createUser                       avgt       3   3.317 ± 0.513   ms/op
ClientGrpc.existUser                        avgt       3   3.099 ± 1.408   ms/op
ClientGrpc.getUser                          avgt       3   3.209 ± 0.601   ms/op
ClientGrpc.listUser                         avgt       3   4.115 ± 0.329   ms/op
ClientGrpc.createUser                     sample  303223   3.166 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.664           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.018           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.215           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.302           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.726           ms/op
ClientGrpc.existUser                      sample  303926   3.156 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.751           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.117           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.842           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.022           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.376           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.759           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.151           ms/op
ClientGrpc.getUser                        sample  300728   3.191 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.861           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.588           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.317           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.661           ms/op
ClientGrpc.listUser                       sample  236790   4.053 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.098           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.895           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.063           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.647           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.094           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.246           ms/op
