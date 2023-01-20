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
# Warmup Iteration   1: 4.845 ops/ms
# Warmup Iteration   2: 9.562 ops/ms
# Warmup Iteration   3: 10.382 ops/ms
Iteration   1: 10.448 ops/ms
Iteration   2: 10.582 ops/ms
Iteration   3: 10.236 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.422 ±(99.9%) 3.183 ops/ms [Average]
  (min, avg, max) = (10.236, 10.422, 10.582), stdev = 0.174
  CI (99.9%): [7.239, 13.606] (assumes normal distribution)


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
# Warmup Iteration   1: 7.721 ops/ms
# Warmup Iteration   2: 10.392 ops/ms
# Warmup Iteration   3: 10.600 ops/ms
Iteration   1: 10.668 ops/ms
Iteration   2: 10.799 ops/ms
Iteration   3: 10.785 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.750 ±(99.9%) 1.317 ops/ms [Average]
  (min, avg, max) = (10.668, 10.750, 10.799), stdev = 0.072
  CI (99.9%): [9.434, 12.067] (assumes normal distribution)


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
# Warmup Iteration   1: 8.054 ops/ms
# Warmup Iteration   2: 10.427 ops/ms
# Warmup Iteration   3: 10.256 ops/ms
Iteration   1: 10.537 ops/ms
Iteration   2: 10.488 ops/ms
Iteration   3: 10.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.465 ±(99.9%) 1.550 ops/ms [Average]
  (min, avg, max) = (10.371, 10.465, 10.537), stdev = 0.085
  CI (99.9%): [8.916, 12.015] (assumes normal distribution)


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
# Warmup Iteration   1: 6.417 ops/ms
# Warmup Iteration   2: 7.586 ops/ms
# Warmup Iteration   3: 8.012 ops/ms
Iteration   1: 7.879 ops/ms
Iteration   2: 7.883 ops/ms
Iteration   3: 8.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.929 ±(99.9%) 1.518 ops/ms [Average]
  (min, avg, max) = (7.879, 7.929, 8.025), stdev = 0.083
  CI (99.9%): [6.411, 9.447] (assumes normal distribution)


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
# Warmup Iteration   1: 4.045 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.004 ms/op
Iteration   1: 3.169 ±(99.9%) 0.002 ms/op
Iteration   2: 3.075 ±(99.9%) 0.002 ms/op
Iteration   3: 3.174 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.139 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (3.075, 3.139, 3.174), stdev = 0.055
  CI (99.9%): [2.128, 4.150] (assumes normal distribution)


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 3.091 ±(99.9%) 0.001 ms/op
Iteration   2: 2.919 ±(99.9%) 0.002 ms/op
Iteration   3: 3.068 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.026 ±(99.9%) 1.703 ms/op [Average]
  (min, avg, max) = (2.919, 3.026, 3.091), stdev = 0.093
  CI (99.9%): [1.323, 4.730] (assumes normal distribution)


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.002 ms/op
Iteration   1: 3.147 ±(99.9%) 0.002 ms/op
Iteration   2: 3.166 ±(99.9%) 0.002 ms/op
Iteration   3: 3.191 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.168 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (3.147, 3.168, 3.191), stdev = 0.022
  CI (99.9%): [2.768, 3.569] (assumes normal distribution)


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
# Warmup Iteration   1: 5.186 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.256 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.138 ±(99.9%) 0.013 ms/op
Iteration   1: 4.101 ±(99.9%) 0.026 ms/op
Iteration   2: 4.144 ±(99.9%) 0.008 ms/op
Iteration   3: 4.261 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.169 ±(99.9%) 1.509 ms/op [Average]
  (min, avg, max) = (4.101, 4.169, 4.261), stdev = 0.083
  CI (99.9%): [2.659, 5.678] (assumes normal distribution)


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.007 ms/op
Iteration   1: 3.224 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.220 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.102 ms/op
                 createUser·p0.9999: 12.835 ms/op
                 createUser·p1.00:   18.088 ms/op

Iteration   2: 3.167 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.504 ms/op
                 createUser·p0.9999: 13.581 ms/op
                 createUser·p1.00:   14.025 ms/op

Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.722 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.711 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.069 ms/op
                 createUser·p0.9999: 16.051 ms/op
                 createUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303267
  mean =      3.164 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 977 
    [ 1.250,  2.500) = 20584 
    [ 2.500,  3.750) = 242597 
    [ 3.750,  5.000) = 37946 
    [ 5.000,  6.250) = 533 
    [ 6.250,  7.500) = 383 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 42 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.220 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.258 ms/op
     p(99.9900) =     15.652 ms/op
     p(99.9990) =     16.398 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.756 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.007 ms/op
Iteration   1: 3.036 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.774 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.284 ms/op
                 existUser·p0.999:  5.999 ms/op
                 existUser·p0.9999: 11.369 ms/op
                 existUser·p1.00:   11.764 ms/op

Iteration   2: 2.988 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.632 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.543 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  6.806 ms/op
                 existUser·p0.9999: 17.189 ms/op
                 existUser·p1.00:   17.465 ms/op

Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.513 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.074 ms/op
                 existUser·p0.9999: 15.925 ms/op
                 existUser·p1.00:   16.548 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319048
  mean =      3.010 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1212 
    [ 1.250,  2.500) = 41439 
    [ 2.500,  3.750) = 253200 
    [ 3.750,  5.000) = 22379 
    [ 5.000,  6.250) = 495 
    [ 6.250,  7.500) = 149 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.513 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      6.266 ms/op
     p(99.9900) =     16.646 ms/op
     p(99.9990) =     17.394 ms/op
     p(99.9999) =     17.465 ms/op
    p(100.0000) =     17.465 ms/op


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.137 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.007 ms/op
Iteration   1: 3.073 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.920 ms/op
                 getUser·p0.9999: 14.408 ms/op
                 getUser·p1.00:   15.778 ms/op

Iteration   2: 3.103 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.858 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  9.583 ms/op
                 getUser·p0.9999: 17.554 ms/op
                 getUser·p1.00:   17.990 ms/op

Iteration   3: 3.045 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.308 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  6.348 ms/op
                 getUser·p0.9999: 17.662 ms/op
                 getUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312164
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1528 
    [ 1.250,  2.500) = 23151 
    [ 2.500,  3.750) = 265109 
    [ 3.750,  5.000) = 21323 
    [ 5.000,  6.250) = 491 
    [ 6.250,  7.500) = 252 
    [ 7.500,  8.750) = 81 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 40 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.308 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.838 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.460 ms/op
     p(99.9900) =     17.458 ms/op
     p(99.9990) =     18.047 ms/op
     p(99.9999) =     18.153 ms/op
    p(100.0000) =     18.153 ms/op


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
# Warmup Iteration   1: 4.853 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.097 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.989 ±(99.9%) 0.010 ms/op
Iteration   1: 3.980 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 20.249 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   2: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  14.311 ms/op
                 listUser·p0.9999: 20.114 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 3.932 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  18.468 ms/op
                 listUser·p0.9999: 24.019 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243176
  mean =      3.946 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3581 
    [ 2.500,  5.000) = 215080 
    [ 5.000,  7.500) = 23354 
    [ 7.500, 10.000) = 690 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.775 ms/op
     p(99.9000) =     14.035 ms/op
     p(99.9900) =     23.572 ms/op
     p(99.9990) =     26.237 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.422 ± 3.183  ops/ms
ClientGrpc.existUser                       thrpt       3  10.750 ± 1.317  ops/ms
ClientGrpc.getUser                         thrpt       3  10.465 ± 1.550  ops/ms
ClientGrpc.listUser                        thrpt       3   7.929 ± 1.518  ops/ms
ClientGrpc.createUser                       avgt       3   3.139 ± 1.011   ms/op
ClientGrpc.existUser                        avgt       3   3.026 ± 1.703   ms/op
ClientGrpc.getUser                          avgt       3   3.168 ± 0.401   ms/op
ClientGrpc.listUser                         avgt       3   4.169 ± 1.509   ms/op
ClientGrpc.createUser                     sample  303267   3.164 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.220           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.150           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.258           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.652           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.088           ms/op
ClientGrpc.existUser                      sample  319048   3.010 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.513           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.998           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.842           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.266           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.646           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.465           ms/op
ClientGrpc.getUser                        sample  312164   3.073 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.308           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.460           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.458           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.153           ms/op
ClientGrpc.listUser                       sample  243176   3.946 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.895           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.789           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.035           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.572           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.313           ms/op
