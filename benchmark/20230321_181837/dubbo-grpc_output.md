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
# Warmup Iteration   1: 4.044 ops/ms
# Warmup Iteration   2: 8.340 ops/ms
# Warmup Iteration   3: 9.981 ops/ms
Iteration   1: 10.589 ops/ms
Iteration   2: 10.457 ops/ms
Iteration   3: 10.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.461 ±(99.9%) 2.285 ops/ms [Average]
  (min, avg, max) = (10.338, 10.461, 10.589), stdev = 0.125
  CI (99.9%): [8.176, 12.746] (assumes normal distribution)


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
# Warmup Iteration   1: 7.415 ops/ms
# Warmup Iteration   2: 10.276 ops/ms
# Warmup Iteration   3: 10.837 ops/ms
Iteration   1: 10.882 ops/ms
Iteration   2: 10.974 ops/ms
Iteration   3: 11.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.992 ±(99.9%) 2.184 ops/ms [Average]
  (min, avg, max) = (10.882, 10.992, 11.119), stdev = 0.120
  CI (99.9%): [8.807, 13.176] (assumes normal distribution)


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
# Warmup Iteration   1: 6.511 ops/ms
# Warmup Iteration   2: 10.000 ops/ms
# Warmup Iteration   3: 10.345 ops/ms
Iteration   1: 10.489 ops/ms
Iteration   2: 10.502 ops/ms
Iteration   3: 10.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.460 ±(99.9%) 1.142 ops/ms [Average]
  (min, avg, max) = (10.388, 10.460, 10.502), stdev = 0.063
  CI (99.9%): [9.318, 11.601] (assumes normal distribution)


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
# Warmup Iteration   1: 5.791 ops/ms
# Warmup Iteration   2: 7.714 ops/ms
# Warmup Iteration   3: 7.822 ops/ms
Iteration   1: 7.777 ops/ms
Iteration   2: 7.887 ops/ms
Iteration   3: 7.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.826 ±(99.9%) 1.025 ops/ms [Average]
  (min, avg, max) = (7.777, 7.826, 7.887), stdev = 0.056
  CI (99.9%): [6.801, 8.851] (assumes normal distribution)


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.010 ms/op
Iteration   1: 3.085 ±(99.9%) 0.003 ms/op
Iteration   2: 3.087 ±(99.9%) 0.003 ms/op
Iteration   3: 3.088 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.086 ±(99.9%) 0.028 ms/op [Average]
  (min, avg, max) = (3.085, 3.086, 3.088), stdev = 0.002
  CI (99.9%): [3.059, 3.114] (assumes normal distribution)


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
# Warmup Iteration   1: 4.255 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.002 ms/op
Iteration   1: 2.968 ±(99.9%) 0.004 ms/op
Iteration   2: 2.943 ±(99.9%) 0.003 ms/op
Iteration   3: 2.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.943 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (2.917, 2.943, 2.968), stdev = 0.025
  CI (99.9%): [2.481, 3.404] (assumes normal distribution)


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.003 ms/op
Iteration   1: 3.055 ±(99.9%) 0.003 ms/op
Iteration   2: 3.069 ±(99.9%) 0.003 ms/op
Iteration   3: 3.054 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.059 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (3.054, 3.059, 3.069), stdev = 0.008
  CI (99.9%): [2.910, 3.209] (assumes normal distribution)


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
# Warmup Iteration   1: 5.892 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.013 ms/op
Iteration   1: 3.983 ±(99.9%) 0.008 ms/op
Iteration   2: 3.931 ±(99.9%) 0.034 ms/op
Iteration   3: 4.036 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.983 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (3.931, 3.983, 4.036), stdev = 0.053
  CI (99.9%): [3.021, 4.946] (assumes normal distribution)


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
# Warmup Iteration   1: 4.368 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  10.194 ms/op
                 createUser·p0.9999: 13.367 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   2: 3.036 ±(99.9%) 0.004 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   4.149 ms/op
                 createUser·p0.999:  7.275 ms/op
                 createUser·p0.9999: 13.483 ms/op
                 createUser·p1.00:   13.779 ms/op

Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  13.106 ms/op
                 createUser·p0.9999: 18.252 ms/op
                 createUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312247
  mean =      3.074 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 246 
    [ 1.250,  2.500) = 15288 
    [ 2.500,  3.750) = 279954 
    [ 3.750,  5.000) = 15380 
    [ 5.000,  6.250) = 688 
    [ 6.250,  7.500) = 282 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 52 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =     10.256 ms/op
     p(99.9900) =     17.916 ms/op
     p(99.9990) =     18.506 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
Iteration   1: 2.906 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   4.579 ms/op
                 existUser·p0.999:  7.920 ms/op
                 existUser·p0.9999: 12.255 ms/op
                 existUser·p1.00:   12.468 ms/op

Iteration   2: 2.938 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.889 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  7.045 ms/op
                 existUser·p0.9999: 13.802 ms/op
                 existUser·p1.00:   14.090 ms/op

Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.722 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  9.388 ms/op
                 existUser·p0.9999: 18.130 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326214
  mean =      2.943 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 938 
    [ 1.250,  2.500) = 33812 
    [ 2.500,  3.750) = 280292 
    [ 3.750,  5.000) = 9701 
    [ 5.000,  6.250) = 765 
    [ 6.250,  7.500) = 350 
    [ 7.500,  8.750) = 114 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 80 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      7.666 ms/op
     p(99.9900) =     16.482 ms/op
     p(99.9990) =     18.383 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 4.501 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
Iteration   1: 3.067 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.687 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  8.389 ms/op
                 getUser·p0.9999: 24.333 ms/op
                 getUser·p1.00:   24.936 ms/op

Iteration   2: 3.049 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  6.637 ms/op
                 getUser·p0.9999: 22.807 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   3: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.996 ms/op
                 getUser·p0.9999: 22.610 ms/op
                 getUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313930
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17455 
    [ 2.500,  5.000) = 295168 
    [ 5.000,  7.500) = 1028 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.687 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.210 ms/op
     p(99.9900) =     23.187 ms/op
     p(99.9990) =     24.927 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 5.227 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.285 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.969 ±(99.9%) 0.011 ms/op
Iteration   1: 4.087 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.982 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.754 ms/op
                 listUser·p0.9999: 20.955 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   2: 4.019 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  15.179 ms/op
                 listUser·p0.9999: 24.989 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 4.044 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.052 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 25.136 ms/op
                 listUser·p1.00:   25.690 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237165
  mean =      4.050 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2459 
    [ 2.500,  5.000) = 209994 
    [ 5.000,  7.500) = 23335 
    [ 7.500, 10.000) = 936 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.982 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     15.008 ms/op
     p(99.9900) =     24.786 ms/op
     p(99.9990) =     26.038 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.461 ± 2.285  ops/ms
ClientGrpc.existUser                       thrpt       3  10.992 ± 2.184  ops/ms
ClientGrpc.getUser                         thrpt       3  10.460 ± 1.142  ops/ms
ClientGrpc.listUser                        thrpt       3   7.826 ± 1.025  ops/ms
ClientGrpc.createUser                       avgt       3   3.086 ± 0.028   ms/op
ClientGrpc.existUser                        avgt       3   2.943 ± 0.462   ms/op
ClientGrpc.getUser                          avgt       3   3.059 ± 0.149   ms/op
ClientGrpc.listUser                         avgt       3   3.983 ± 0.962   ms/op
ClientGrpc.createUser                     sample  312247   3.074 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.776           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.039           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.256           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.916           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.776           ms/op
ClientGrpc.existUser                      sample  326214   2.943 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.722           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.916           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.621           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.666           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.482           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.383           ms/op
ClientGrpc.getUser                        sample  313930   3.056 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.687           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.210           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.187           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.936           ms/op
ClientGrpc.listUser                       sample  237165   4.050 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.982           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.008           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.786           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.116           ms/op
