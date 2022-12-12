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
# Warmup Iteration   1: 4.324 ops/ms
# Warmup Iteration   2: 8.689 ops/ms
# Warmup Iteration   3: 10.183 ops/ms
Iteration   1: 10.053 ops/ms
Iteration   2: 10.277 ops/ms
Iteration   3: 10.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.145 ±(99.9%) 2.130 ops/ms [Average]
  (min, avg, max) = (10.053, 10.145, 10.277), stdev = 0.117
  CI (99.9%): [8.015, 12.276] (assumes normal distribution)


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
# Warmup Iteration   1: 7.350 ops/ms
# Warmup Iteration   2: 10.249 ops/ms
# Warmup Iteration   3: 10.517 ops/ms
Iteration   1: 10.535 ops/ms
Iteration   2: 10.614 ops/ms
Iteration   3: 10.412 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.521 ±(99.9%) 1.855 ops/ms [Average]
  (min, avg, max) = (10.412, 10.521, 10.614), stdev = 0.102
  CI (99.9%): [8.665, 12.376] (assumes normal distribution)


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
# Warmup Iteration   1: 6.702 ops/ms
# Warmup Iteration   2: 10.023 ops/ms
# Warmup Iteration   3: 10.184 ops/ms
Iteration   1: 9.998 ops/ms
Iteration   2: 10.024 ops/ms
Iteration   3: 10.246 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.089 ±(99.9%) 2.494 ops/ms [Average]
  (min, avg, max) = (9.998, 10.089, 10.246), stdev = 0.137
  CI (99.9%): [7.595, 12.584] (assumes normal distribution)


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
# Warmup Iteration   1: 5.402 ops/ms
# Warmup Iteration   2: 7.597 ops/ms
# Warmup Iteration   3: 7.803 ops/ms
Iteration   1: 7.952 ops/ms
Iteration   2: 8.065 ops/ms
Iteration   3: 8.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.013 ±(99.9%) 1.032 ops/ms [Average]
  (min, avg, max) = (7.952, 8.013, 8.065), stdev = 0.057
  CI (99.9%): [6.981, 9.045] (assumes normal distribution)


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.008 ms/op
Iteration   1: 3.192 ±(99.9%) 0.002 ms/op
Iteration   2: 3.161 ±(99.9%) 0.002 ms/op
Iteration   3: 3.252 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.202 ±(99.9%) 0.844 ms/op [Average]
  (min, avg, max) = (3.161, 3.202, 3.252), stdev = 0.046
  CI (99.9%): [2.357, 4.046] (assumes normal distribution)


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
# Warmup Iteration   1: 4.136 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.002 ms/op
Iteration   1: 2.965 ±(99.9%) 0.003 ms/op
Iteration   2: 2.963 ±(99.9%) 0.002 ms/op
Iteration   3: 3.023 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.984 ±(99.9%) 0.617 ms/op [Average]
  (min, avg, max) = (2.963, 2.984, 3.023), stdev = 0.034
  CI (99.9%): [2.367, 3.600] (assumes normal distribution)


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.003 ms/op
Iteration   1: 3.160 ±(99.9%) 0.003 ms/op
Iteration   2: 3.155 ±(99.9%) 0.004 ms/op
Iteration   3: 3.107 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.140 ±(99.9%) 0.535 ms/op [Average]
  (min, avg, max) = (3.107, 3.140, 3.160), stdev = 0.029
  CI (99.9%): [2.605, 3.675] (assumes normal distribution)


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
# Warmup Iteration   1: 5.718 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.182 ±(99.9%) 0.011 ms/op
Iteration   1: 4.037 ±(99.9%) 0.008 ms/op
Iteration   2: 3.994 ±(99.9%) 0.007 ms/op
Iteration   3: 4.060 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.030 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (3.994, 4.030, 4.060), stdev = 0.034
  CI (99.9%): [3.412, 4.648] (assumes normal distribution)


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
# Warmup Iteration   1: 4.256 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.006 ms/op
Iteration   1: 3.201 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.096 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  9.766 ms/op
                 createUser·p0.9999: 13.435 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.578 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  8.228 ms/op
                 createUser·p0.9999: 21.561 ms/op
                 createUser·p1.00:   21.955 ms/op

Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.336 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  11.108 ms/op
                 createUser·p0.9999: 23.789 ms/op
                 createUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304159
  mean =      3.158 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23152 
    [ 2.500,  5.000) = 279323 
    [ 5.000,  7.500) = 1193 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      9.402 ms/op
     p(99.9900) =     21.286 ms/op
     p(99.9990) =     25.164 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 4.052 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.097 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.746 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.826 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.822 ms/op
                 existUser·p0.9999: 13.845 ms/op
                 existUser·p1.00:   14.352 ms/op

Iteration   2: 3.033 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   3.971 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.778 ms/op
                 existUser·p0.9999: 14.767 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   3.920 ms/op
                 existUser·p0.99:   4.426 ms/op
                 existUser·p0.999:  8.167 ms/op
                 existUser·p0.9999: 17.676 ms/op
                 existUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314432
  mean =      3.051 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1395 
    [ 1.250,  2.500) = 44471 
    [ 2.500,  3.750) = 233368 
    [ 3.750,  5.000) = 33772 
    [ 5.000,  6.250) = 705 
    [ 6.250,  7.500) = 380 
    [ 7.500,  8.750) = 163 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 12 
    [12.500, 13.750) = 39 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.741 ms/op
     p(99.9900) =     15.590 ms/op
     p(99.9990) =     17.947 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


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
# Warmup Iteration   1: 4.280 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
Iteration   1: 3.212 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.797 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.514 ms/op
                 getUser·p0.9999: 13.288 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   2: 3.192 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.500 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   4.612 ms/op
                 getUser·p0.999:  8.517 ms/op
                 getUser·p0.9999: 15.416 ms/op
                 getUser·p1.00:   15.729 ms/op

Iteration   3: 3.238 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  6.979 ms/op
                 getUser·p0.9999: 28.545 ms/op
                 getUser·p1.00:   30.245 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298582
  mean =      3.214 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18630 
    [ 2.500,  5.000) = 278327 
    [ 5.000,  7.500) = 1236 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.500 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.105 ms/op
     p(99.9900) =     27.801 ms/op
     p(99.9990) =     30.051 ms/op
     p(99.9999) =     30.245 ms/op
    p(100.0000) =     30.245 ms/op


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.370 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.011 ms/op
Iteration   1: 4.059 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.018 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   6.054 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  13.767 ms/op
                 listUser·p0.9999: 21.761 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 4.060 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.702 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  16.851 ms/op
                 listUser·p0.9999: 27.697 ms/op
                 listUser·p1.00:   28.049 ms/op

Iteration   3: 4.038 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.005 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  19.532 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236992
  mean =      4.052 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3201 
    [ 2.500,  5.000) = 203959 
    [ 5.000,  7.500) = 28463 
    [ 7.500, 10.000) = 960 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      5.216 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.004 ms/op
     p(99.9000) =     16.417 ms/op
     p(99.9900) =     27.175 ms/op
     p(99.9990) =     28.005 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.145 ± 2.130  ops/ms
ClientGrpc.existUser                       thrpt       3  10.521 ± 1.855  ops/ms
ClientGrpc.getUser                         thrpt       3  10.089 ± 2.494  ops/ms
ClientGrpc.listUser                        thrpt       3   8.013 ± 1.032  ops/ms
ClientGrpc.createUser                       avgt       3   3.202 ± 0.844   ms/op
ClientGrpc.existUser                        avgt       3   2.984 ± 0.617   ms/op
ClientGrpc.getUser                          avgt       3   3.140 ± 0.535   ms/op
ClientGrpc.listUser                         avgt       3   4.030 ± 0.618   ms/op
ClientGrpc.createUser                     sample  304159   3.158 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.336           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.402           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.286           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.264           ms/op
ClientGrpc.existUser                      sample  314432   3.051 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.746           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.043           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.969           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.741           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.590           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.088           ms/op
ClientGrpc.getUser                        sample  298582   3.214 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.500           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.183           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.096           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.105           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.801           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.245           ms/op
ClientGrpc.listUser                       sample  236992   4.052 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.702           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.216           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.004           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.417           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.175           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.049           ms/op
