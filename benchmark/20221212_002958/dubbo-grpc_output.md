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
# Warmup Iteration   1: 4.727 ops/ms
# Warmup Iteration   2: 9.048 ops/ms
# Warmup Iteration   3: 10.432 ops/ms
Iteration   1: 10.317 ops/ms
Iteration   2: 10.171 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.337 ±(99.9%) 3.217 ops/ms [Average]
  (min, avg, max) = (10.171, 10.337, 10.522), stdev = 0.176
  CI (99.9%): [7.120, 13.553] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.778 ops/ms
# Warmup Iteration   2: 10.792 ops/ms
# Warmup Iteration   3: 10.761 ops/ms
Iteration   1: 10.734 ops/ms
Iteration   2: 11.133 ops/ms
Iteration   3: 10.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.907 ±(99.9%) 3.737 ops/ms [Average]
  (min, avg, max) = (10.734, 10.907, 11.133), stdev = 0.205
  CI (99.9%): [7.170, 14.645] (assumes normal distribution)


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
# Warmup Iteration   1: 7.490 ops/ms
# Warmup Iteration   2: 10.395 ops/ms
# Warmup Iteration   3: 10.482 ops/ms
Iteration   1: 10.172 ops/ms
Iteration   2: 10.476 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.360 ±(99.9%) 2.997 ops/ms [Average]
  (min, avg, max) = (10.172, 10.360, 10.476), stdev = 0.164
  CI (99.9%): [7.364, 13.357] (assumes normal distribution)


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
# Warmup Iteration   1: 5.943 ops/ms
# Warmup Iteration   2: 7.432 ops/ms
# Warmup Iteration   3: 7.921 ops/ms
Iteration   1: 8.144 ops/ms
Iteration   2: 7.949 ops/ms
Iteration   3: 8.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.031 ±(99.9%) 1.845 ops/ms [Average]
  (min, avg, max) = (7.949, 8.031, 8.144), stdev = 0.101
  CI (99.9%): [6.186, 9.876] (assumes normal distribution)


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.117 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.002 ms/op
Iteration   1: 3.069 ±(99.9%) 0.003 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.120 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.098 ±(99.9%) 0.479 ms/op [Average]
  (min, avg, max) = (3.069, 3.098, 3.120), stdev = 0.026
  CI (99.9%): [2.620, 3.577] (assumes normal distribution)


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
# Warmup Iteration   1: 3.654 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.011 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.004 ms/op
Iteration   1: 2.932 ±(99.9%) 0.003 ms/op
Iteration   2: 3.025 ±(99.9%) 0.001 ms/op
Iteration   3: 3.012 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.990 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (2.932, 2.990, 3.025), stdev = 0.051
  CI (99.9%): [2.068, 3.912] (assumes normal distribution)


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
# Warmup Iteration   1: 4.132 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 3.137 ±(99.9%) 0.004 ms/op
Iteration   2: 3.037 ±(99.9%) 0.001 ms/op
Iteration   3: 3.057 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.077 ±(99.9%) 0.957 ms/op [Average]
  (min, avg, max) = (3.037, 3.077, 3.137), stdev = 0.052
  CI (99.9%): [2.120, 4.034] (assumes normal distribution)


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
# Warmup Iteration   1: 5.401 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.303 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.229 ±(99.9%) 0.019 ms/op
Iteration   1: 4.181 ±(99.9%) 0.010 ms/op
Iteration   2: 4.186 ±(99.9%) 0.012 ms/op
Iteration   3: 4.143 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.170 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (4.143, 4.170, 4.186), stdev = 0.024
  CI (99.9%): [3.734, 4.606] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.024 ±(99.9%) 0.006 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.039 ms/op
                 createUser·p0.9999: 22.206 ms/op
                 createUser·p1.00:   22.839 ms/op

Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  11.576 ms/op
                 createUser·p0.9999: 13.580 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   3: 3.132 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.817 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.977 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306266
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24836 
    [ 2.500,  5.000) = 280374 
    [ 5.000,  7.500) = 662 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.191 ms/op
     p(99.9900) =     23.069 ms/op
     p(99.9990) =     24.312 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 3.836 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.929 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  5.225 ms/op
                 existUser·p0.9999: 11.783 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.695 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  9.695 ms/op
                 existUser·p0.9999: 14.924 ms/op
                 existUser·p1.00:   15.221 ms/op

Iteration   3: 3.005 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.720 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  7.656 ms/op
                 existUser·p0.9999: 14.566 ms/op
                 existUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321217
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1512 
    [ 1.250,  2.500) = 45109 
    [ 2.500,  3.750) = 252042 
    [ 3.750,  5.000) = 21821 
    [ 5.000,  6.250) = 287 
    [ 6.250,  7.500) = 167 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 14 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.170 ms/op
     p(99.9000) =      7.176 ms/op
     p(99.9900) =     14.531 ms/op
     p(99.9990) =     15.125 ms/op
     p(99.9999) =     15.221 ms/op
    p(100.0000) =     15.221 ms/op


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
# Warmup Iteration   1: 3.253 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  9.491 ms/op
                 getUser·p0.9999: 11.633 ms/op
                 getUser·p1.00:   12.288 ms/op

Iteration   2: 3.113 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.241 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.520 ms/op
                 getUser·p0.9999: 20.438 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.856 ms/op
                 getUser·p0.9999: 25.769 ms/op
                 getUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308244
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21442 
    [ 2.500,  5.000) = 285691 
    [ 5.000,  7.500) = 741 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.241 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      8.043 ms/op
     p(99.9900) =     24.528 ms/op
     p(99.9990) =     26.231 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 5.448 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.012 ms/op
Iteration   1: 3.985 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  12.300 ms/op
                 listUser·p0.9999: 13.730 ms/op
                 listUser·p1.00:   14.189 ms/op

Iteration   2: 4.047 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.755 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 23.003 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   3: 3.954 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.305 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.385 ms/op
                 listUser·p0.9999: 21.650 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240259
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5589 
    [ 2.500,  5.000) = 206304 
    [ 5.000,  7.500) = 26828 
    [ 7.500, 10.000) = 932 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 157 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 93 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.305 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.169 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     14.987 ms/op
     p(99.9900) =     22.052 ms/op
     p(99.9990) =     23.258 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.337 ± 3.217  ops/ms
ClientGrpc.existUser                       thrpt       3  10.907 ± 3.737  ops/ms
ClientGrpc.getUser                         thrpt       3  10.360 ± 2.997  ops/ms
ClientGrpc.listUser                        thrpt       3   8.031 ± 1.845  ops/ms
ClientGrpc.createUser                       avgt       3   3.098 ± 0.479   ms/op
ClientGrpc.existUser                        avgt       3   2.990 ± 0.922   ms/op
ClientGrpc.getUser                          avgt       3   3.077 ± 0.957   ms/op
ClientGrpc.listUser                         avgt       3   4.170 ± 0.436   ms/op
ClientGrpc.createUser                     sample  306266   3.132 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.674           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.113           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.985           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.191           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.069           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.314           ms/op
ClientGrpc.existUser                      sample  321217   2.987 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.695           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.176           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.531           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.221           ms/op
ClientGrpc.getUser                        sample  308244   3.115 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.241           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.092           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.953           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.043           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.528           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.345           ms/op
ClientGrpc.listUser                       sample  240259   3.995 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.305           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.830           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.987           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.052           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.364           ms/op
