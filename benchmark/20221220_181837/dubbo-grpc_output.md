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
# Warmup Iteration   1: 4.757 ops/ms
# Warmup Iteration   2: 8.876 ops/ms
# Warmup Iteration   3: 10.354 ops/ms
Iteration   1: 10.353 ops/ms
Iteration   2: 10.136 ops/ms
Iteration   3: 10.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.281 ±(99.9%) 2.283 ops/ms [Average]
  (min, avg, max) = (10.136, 10.281, 10.354), stdev = 0.125
  CI (99.9%): [7.998, 12.564] (assumes normal distribution)


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
# Warmup Iteration   1: 8.361 ops/ms
# Warmup Iteration   2: 10.477 ops/ms
# Warmup Iteration   3: 10.737 ops/ms
Iteration   1: 11.032 ops/ms
Iteration   2: 11.051 ops/ms
Iteration   3: 10.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.022 ±(99.9%) 0.639 ops/ms [Average]
  (min, avg, max) = (10.983, 11.022, 11.051), stdev = 0.035
  CI (99.9%): [10.383, 11.661] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.338 ops/ms
# Warmup Iteration   2: 10.432 ops/ms
# Warmup Iteration   3: 10.520 ops/ms
Iteration   1: 10.434 ops/ms
Iteration   2: 10.804 ops/ms
Iteration   3: 10.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.639 ±(99.9%) 3.434 ops/ms [Average]
  (min, avg, max) = (10.434, 10.639, 10.804), stdev = 0.188
  CI (99.9%): [7.205, 14.073] (assumes normal distribution)


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
# Warmup Iteration   1: 5.401 ops/ms
# Warmup Iteration   2: 7.902 ops/ms
# Warmup Iteration   3: 8.128 ops/ms
Iteration   1: 8.320 ops/ms
Iteration   2: 8.220 ops/ms
Iteration   3: 8.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.303 ±(99.9%) 1.390 ops/ms [Average]
  (min, avg, max) = (8.220, 8.303, 8.369), stdev = 0.076
  CI (99.9%): [6.913, 9.693] (assumes normal distribution)


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.003 ms/op
Iteration   1: 3.070 ±(99.9%) 0.002 ms/op
Iteration   2: 3.123 ±(99.9%) 0.002 ms/op
Iteration   3: 3.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.101 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (3.070, 3.101, 3.123), stdev = 0.028
  CI (99.9%): [2.595, 3.606] (assumes normal distribution)


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
# Warmup Iteration   1: 3.794 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.875 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.002 ms/op
Iteration   2: 2.984 ±(99.9%) 0.002 ms/op
Iteration   3: 2.903 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.949 ±(99.9%) 0.764 ms/op [Average]
  (min, avg, max) = (2.903, 2.949, 2.984), stdev = 0.042
  CI (99.9%): [2.185, 3.714] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.937 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.002 ms/op
Iteration   1: 3.055 ±(99.9%) 0.002 ms/op
Iteration   2: 3.054 ±(99.9%) 0.003 ms/op
Iteration   3: 3.078 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (3.054, 3.062, 3.078), stdev = 0.013
  CI (99.9%): [2.816, 3.308] (assumes normal distribution)


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
# Warmup Iteration   1: 5.257 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.028 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.010 ms/op
Iteration   1: 3.870 ±(99.9%) 0.030 ms/op
Iteration   2: 4.023 ±(99.9%) 0.037 ms/op
Iteration   3: 3.922 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.939 ±(99.9%) 1.421 ms/op [Average]
  (min, avg, max) = (3.870, 3.939, 4.023), stdev = 0.078
  CI (99.9%): [2.518, 5.360] (assumes normal distribution)


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
# Warmup Iteration   1: 3.962 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.012 ms/op
Iteration   1: 2.996 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.510 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.576 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  6.871 ms/op
                 createUser·p0.9999: 11.282 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  7.967 ms/op
                 createUser·p0.9999: 18.769 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   3: 3.128 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.809 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.742 ms/op
                 createUser·p0.9999: 14.562 ms/op
                 createUser·p1.00:   14.762 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311295
  mean =      3.083 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1681 
    [ 1.250,  2.500) = 21934 
    [ 2.500,  3.750) = 262395 
    [ 3.750,  5.000) = 24383 
    [ 5.000,  6.250) = 379 
    [ 6.250,  7.500) = 211 
    [ 7.500,  8.750) = 105 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.526 ms/op
     p(99.9900) =     18.051 ms/op
     p(99.9990) =     19.023 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 3.749 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.846 ms/op
                 existUser·p0.9999: 15.057 ms/op
                 existUser·p1.00:   15.254 ms/op

Iteration   2: 2.908 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  6.316 ms/op
                 existUser·p0.9999: 15.172 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   3: 2.975 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  7.879 ms/op
                 existUser·p0.9999: 15.934 ms/op
                 existUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326024
  mean =      2.942 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2119 
    [ 1.250,  2.500) = 38397 
    [ 2.500,  3.750) = 272545 
    [ 3.750,  5.000) = 11931 
    [ 5.000,  6.250) = 478 
    [ 6.250,  7.500) = 222 
    [ 7.500,  8.750) = 148 
    [ 8.750, 10.000) = 28 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.465 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.544 ms/op
     p(99.9900) =     15.211 ms/op
     p(99.9990) =     16.453 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 3.874 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
Iteration   1: 3.168 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  6.756 ms/op
                 getUser·p0.9999: 12.217 ms/op
                 getUser·p1.00:   12.534 ms/op

Iteration   2: 3.119 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.057 ms/op
                 getUser·p0.9999: 13.234 ms/op
                 getUser·p1.00:   13.566 ms/op

Iteration   3: 3.130 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.979 ms/op
                 getUser·p0.9999: 16.331 ms/op
                 getUser·p1.00:   16.810 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305952
  mean =      3.139 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1272 
    [ 1.250,  2.500) = 20959 
    [ 2.500,  3.750) = 245643 
    [ 3.750,  5.000) = 37105 
    [ 5.000,  6.250) = 489 
    [ 6.250,  7.500) = 207 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.102 ms/op
     p(99.9900) =     15.440 ms/op
     p(99.9990) =     16.675 ms/op
     p(99.9999) =     16.810 ms/op
    p(100.0000) =     16.810 ms/op


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
# Warmup Iteration   1: 4.293 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.012 ms/op
Iteration   1: 3.813 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.016 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  16.056 ms/op
                 listUser·p0.9999: 28.483 ms/op
                 listUser·p1.00:   29.098 ms/op

Iteration   2: 3.848 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.963 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.504 ms/op
                 listUser·p0.999:  15.032 ms/op
                 listUser·p0.9999: 22.643 ms/op
                 listUser·p1.00:   23.658 ms/op

Iteration   3: 3.869 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.316 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249769
  mean =      3.843 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5708 
    [ 2.500,  5.000) = 222872 
    [ 5.000,  7.500) = 20204 
    [ 7.500, 10.000) = 543 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      6.578 ms/op
     p(99.9000) =     15.234 ms/op
     p(99.9900) =     26.903 ms/op
     p(99.9990) =     28.918 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.281 ± 2.283  ops/ms
ClientGrpc.existUser                       thrpt       3  11.022 ± 0.639  ops/ms
ClientGrpc.getUser                         thrpt       3  10.639 ± 3.434  ops/ms
ClientGrpc.listUser                        thrpt       3   8.303 ± 1.390  ops/ms
ClientGrpc.createUser                       avgt       3   3.101 ± 0.505   ms/op
ClientGrpc.existUser                        avgt       3   2.949 ± 0.764   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 0.246   ms/op
ClientGrpc.listUser                         avgt       3   3.939 ± 1.421   ms/op
ClientGrpc.createUser                     sample  311295   3.083 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.510           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.526           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.051           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.071           ms/op
ClientGrpc.existUser                      sample  326024   2.942 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.670           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.465           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.682           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.544           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.211           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.744           ms/op
ClientGrpc.getUser                        sample  305952   3.139 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.701           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.102           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.440           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.810           ms/op
ClientGrpc.listUser                       sample  249769   3.843 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.963           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.699           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.234           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.903           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.098           ms/op
