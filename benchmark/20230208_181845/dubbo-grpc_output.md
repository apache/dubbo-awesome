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
# Warmup Iteration   1: 4.237 ops/ms
# Warmup Iteration   2: 9.161 ops/ms
# Warmup Iteration   3: 10.006 ops/ms
Iteration   1: 10.453 ops/ms
Iteration   2: 10.300 ops/ms
Iteration   3: 10.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.317 ±(99.9%) 2.318 ops/ms [Average]
  (min, avg, max) = (10.200, 10.317, 10.453), stdev = 0.127
  CI (99.9%): [7.999, 12.636] (assumes normal distribution)


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
# Warmup Iteration   1: 8.074 ops/ms
# Warmup Iteration   2: 10.463 ops/ms
# Warmup Iteration   3: 10.288 ops/ms
Iteration   1: 10.231 ops/ms
Iteration   2: 10.473 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.446 ±(99.9%) 3.683 ops/ms [Average]
  (min, avg, max) = (10.231, 10.446, 10.632), stdev = 0.202
  CI (99.9%): [6.763, 14.128] (assumes normal distribution)


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
# Warmup Iteration   1: 7.284 ops/ms
# Warmup Iteration   2: 9.999 ops/ms
# Warmup Iteration   3: 10.102 ops/ms
Iteration   1: 10.155 ops/ms
Iteration   2: 10.128 ops/ms
Iteration   3: 10.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.202 ±(99.9%) 1.909 ops/ms [Average]
  (min, avg, max) = (10.128, 10.202, 10.321), stdev = 0.105
  CI (99.9%): [8.293, 12.110] (assumes normal distribution)


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
# Warmup Iteration   1: 6.490 ops/ms
# Warmup Iteration   2: 7.517 ops/ms
# Warmup Iteration   3: 7.901 ops/ms
Iteration   1: 7.976 ops/ms
Iteration   2: 7.771 ops/ms
Iteration   3: 8.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.919 ±(99.9%) 2.349 ops/ms [Average]
  (min, avg, max) = (7.771, 7.919, 8.009), stdev = 0.129
  CI (99.9%): [5.570, 10.268] (assumes normal distribution)


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.270 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.003 ms/op
Iteration   1: 3.195 ±(99.9%) 0.002 ms/op
Iteration   2: 3.169 ±(99.9%) 0.002 ms/op
Iteration   3: 3.180 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.181 ±(99.9%) 0.235 ms/op [Average]
  (min, avg, max) = (3.169, 3.181, 3.195), stdev = 0.013
  CI (99.9%): [2.946, 3.416] (assumes normal distribution)


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
# Warmup Iteration   1: 3.756 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.002 ms/op
Iteration   1: 3.084 ±(99.9%) 0.001 ms/op
Iteration   2: 2.966 ±(99.9%) 0.002 ms/op
Iteration   3: 3.028 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.026 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (2.966, 3.026, 3.084), stdev = 0.059
  CI (99.9%): [1.946, 4.106] (assumes normal distribution)


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
# Warmup Iteration   1: 4.286 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.169 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.004 ms/op
Iteration   1: 3.186 ±(99.9%) 0.002 ms/op
Iteration   2: 3.062 ±(99.9%) 0.003 ms/op
Iteration   3: 3.044 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.097 ±(99.9%) 1.410 ms/op [Average]
  (min, avg, max) = (3.044, 3.097, 3.186), stdev = 0.077
  CI (99.9%): [1.687, 4.508] (assumes normal distribution)


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
# Warmup Iteration   1: 5.287 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.019 ms/op
Iteration   1: 4.038 ±(99.9%) 0.009 ms/op
Iteration   2: 3.956 ±(99.9%) 0.019 ms/op
Iteration   3: 3.865 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.953 ±(99.9%) 1.573 ms/op [Average]
  (min, avg, max) = (3.865, 3.953, 4.038), stdev = 0.086
  CI (99.9%): [2.380, 5.526] (assumes normal distribution)


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
# Warmup Iteration   1: 3.868 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.746 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.173 ms/op
                 createUser·p0.9999: 16.993 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   2: 3.105 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  10.338 ms/op
                 createUser·p0.9999: 18.298 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   3: 3.037 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.695 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  7.283 ms/op
                 createUser·p0.9999: 22.656 ms/op
                 createUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312573
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23991 
    [ 2.500,  5.000) = 287523 
    [ 5.000,  7.500) = 750 
    [ 7.500, 10.000) = 72 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      7.466 ms/op
     p(99.9900) =     22.085 ms/op
     p(99.9990) =     24.113 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.047 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.007 ms/op
Iteration   1: 3.005 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.115 ms/op
                 existUser·p0.9999: 12.038 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.724 ms/op
                 existUser·p0.50:   3.052 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.640 ms/op
                 existUser·p0.9999: 14.651 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.663 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.916 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.905 ms/op
                 existUser·p0.9999: 16.483 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315738
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2167 
    [ 1.250,  2.500) = 32451 
    [ 2.500,  3.750) = 253170 
    [ 3.750,  5.000) = 26581 
    [ 5.000,  6.250) = 738 
    [ 6.250,  7.500) = 307 
    [ 7.500,  8.750) = 142 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 12 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.663 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.553 ms/op
     p(99.9900) =     16.094 ms/op
     p(99.9990) =     16.622 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 4.261 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.007 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   4.809 ms/op
                 getUser·p0.999:  8.258 ms/op
                 getUser·p0.9999: 16.066 ms/op
                 getUser·p1.00:   18.612 ms/op

Iteration   2: 3.231 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.555 ms/op
                 getUser·p0.999:  8.003 ms/op
                 getUser·p0.9999: 15.976 ms/op
                 getUser·p1.00:   16.138 ms/op

Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  7.651 ms/op
                 getUser·p0.9999: 14.086 ms/op
                 getUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303367
  mean =      3.164 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1336 
    [ 1.250,  2.500) = 17683 
    [ 2.500,  3.750) = 252998 
    [ 3.750,  5.000) = 29567 
    [ 5.000,  6.250) = 864 
    [ 6.250,  7.500) = 487 
    [ 7.500,  8.750) = 257 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 62 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      7.976 ms/op
     p(99.9900) =     15.920 ms/op
     p(99.9990) =     18.380 ms/op
     p(99.9999) =     18.612 ms/op
    p(100.0000) =     18.612 ms/op


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
# Warmup Iteration   1: 4.741 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.105 ±(99.9%) 0.011 ms/op
Iteration   1: 4.103 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.964 ms/op
                 listUser·p0.999:  13.271 ms/op
                 listUser·p0.9999: 16.138 ms/op
                 listUser·p1.00:   16.744 ms/op

Iteration   2: 4.086 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 24.107 ms/op
                 listUser·p1.00:   25.854 ms/op

Iteration   3: 4.022 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.628 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  13.250 ms/op
                 listUser·p0.9999: 25.366 ms/op
                 listUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235917
  mean =      4.070 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2335 
    [ 2.500,  5.000) = 204180 
    [ 5.000,  7.500) = 28056 
    [ 7.500, 10.000) = 947 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.194 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.042 ms/op
     p(99.9900) =     24.125 ms/op
     p(99.9990) =     25.896 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.317 ± 2.318  ops/ms
ClientGrpc.existUser                       thrpt       3  10.446 ± 3.683  ops/ms
ClientGrpc.getUser                         thrpt       3  10.202 ± 1.909  ops/ms
ClientGrpc.listUser                        thrpt       3   7.919 ± 2.349  ops/ms
ClientGrpc.createUser                       avgt       3   3.181 ± 0.235   ms/op
ClientGrpc.existUser                        avgt       3   3.026 ± 1.080   ms/op
ClientGrpc.getUser                          avgt       3   3.097 ± 1.410   ms/op
ClientGrpc.listUser                         avgt       3   3.953 ± 1.573   ms/op
ClientGrpc.createUser                     sample  312573   3.072 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.611           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.822           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.466           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.085           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.510           ms/op
ClientGrpc.existUser                      sample  315738   3.041 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.663           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.031           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.711           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.912           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.553           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.094           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.236           ms/op
ClientGrpc.getUser                        sample  303367   3.164 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.646           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.620           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.976           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.920           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.612           ms/op
ClientGrpc.listUser                       sample  235917   4.070 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.628           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.194           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.042           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.125           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.018           ms/op
