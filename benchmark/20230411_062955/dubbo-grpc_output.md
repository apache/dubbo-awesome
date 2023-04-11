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
# Warmup Iteration   1: 4.335 ops/ms
# Warmup Iteration   2: 8.593 ops/ms
# Warmup Iteration   3: 9.849 ops/ms
Iteration   1: 10.539 ops/ms
Iteration   2: 10.287 ops/ms
Iteration   3: 10.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.522 ±(99.9%) 4.145 ops/ms [Average]
  (min, avg, max) = (10.287, 10.522, 10.740), stdev = 0.227
  CI (99.9%): [6.377, 14.666] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.186 ops/ms
# Warmup Iteration   2: 10.752 ops/ms
# Warmup Iteration   3: 11.063 ops/ms
Iteration   1: 11.277 ops/ms
Iteration   2: 11.107 ops/ms
Iteration   3: 11.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.195 ±(99.9%) 1.561 ops/ms [Average]
  (min, avg, max) = (11.107, 11.195, 11.277), stdev = 0.086
  CI (99.9%): [9.634, 12.756] (assumes normal distribution)


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
# Warmup Iteration   1: 7.563 ops/ms
# Warmup Iteration   2: 10.078 ops/ms
# Warmup Iteration   3: 10.532 ops/ms
Iteration   1: 10.653 ops/ms
Iteration   2: 10.664 ops/ms
Iteration   3: 10.632 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.650 ±(99.9%) 0.298 ops/ms [Average]
  (min, avg, max) = (10.632, 10.650, 10.664), stdev = 0.016
  CI (99.9%): [10.352, 10.947] (assumes normal distribution)


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
# Warmup Iteration   1: 5.428 ops/ms
# Warmup Iteration   2: 7.688 ops/ms
# Warmup Iteration   3: 7.900 ops/ms
Iteration   1: 8.072 ops/ms
Iteration   2: 7.963 ops/ms
Iteration   3: 8.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.040 ±(99.9%) 1.219 ops/ms [Average]
  (min, avg, max) = (7.963, 8.040, 8.084), stdev = 0.067
  CI (99.9%): [6.821, 9.258] (assumes normal distribution)


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
# Warmup Iteration   1: 4.095 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.009 ms/op
Iteration   1: 3.053 ±(99.9%) 0.003 ms/op
Iteration   2: 2.976 ±(99.9%) 0.003 ms/op
Iteration   3: 3.004 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.011 ±(99.9%) 0.715 ms/op [Average]
  (min, avg, max) = (2.976, 3.011, 3.053), stdev = 0.039
  CI (99.9%): [2.296, 3.726] (assumes normal distribution)


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
# Warmup Iteration   1: 4.187 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.927 ±(99.9%) 0.003 ms/op
Iteration   1: 2.880 ±(99.9%) 0.003 ms/op
Iteration   2: 2.865 ±(99.9%) 0.003 ms/op
Iteration   3: 2.867 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.870 ±(99.9%) 0.149 ms/op [Average]
  (min, avg, max) = (2.865, 2.870, 2.880), stdev = 0.008
  CI (99.9%): [2.721, 3.020] (assumes normal distribution)


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
# Warmup Iteration   1: 4.328 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.004 ms/op
Iteration   1: 3.012 ±(99.9%) 0.002 ms/op
Iteration   2: 2.980 ±(99.9%) 0.002 ms/op
Iteration   3: 2.987 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.993 ±(99.9%) 0.311 ms/op [Average]
  (min, avg, max) = (2.980, 2.993, 3.012), stdev = 0.017
  CI (99.9%): [2.681, 3.304] (assumes normal distribution)


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.017 ms/op
Iteration   1: 3.933 ±(99.9%) 0.010 ms/op
Iteration   2: 3.861 ±(99.9%) 0.014 ms/op
Iteration   3: 3.915 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.903 ±(99.9%) 0.689 ms/op [Average]
  (min, avg, max) = (3.861, 3.903, 3.933), stdev = 0.038
  CI (99.9%): [3.214, 4.592] (assumes normal distribution)


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
# Warmup Iteration   1: 4.265 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 2.978 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.383 ms/op
                 createUser·p0.95:   3.551 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.600 ms/op
                 createUser·p0.9999: 12.648 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   2: 3.012 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.405 ms/op
                 createUser·p0.9999: 13.775 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  10.685 ms/op
                 createUser·p0.9999: 18.711 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318301
  mean =      3.017 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 692 
    [ 1.250,  2.500) = 25018 
    [ 2.500,  3.750) = 277226 
    [ 3.750,  5.000) = 14114 
    [ 5.000,  6.250) = 645 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 34 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.536 ms/op
     p(99.9900) =     17.476 ms/op
     p(99.9990) =     18.711 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.916 ±(99.9%) 0.005 ms/op
Iteration   1: 2.870 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.783 ms/op
                 existUser·p0.9999: 12.452 ms/op
                 existUser·p1.00:   13.107 ms/op

Iteration   2: 2.888 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  5.917 ms/op
                 existUser·p0.9999: 14.479 ms/op
                 existUser·p1.00:   14.729 ms/op

Iteration   3: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  9.945 ms/op
                 existUser·p0.9999: 19.564 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331717
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47140 
    [ 2.500,  5.000) = 283505 
    [ 5.000,  7.500) = 705 
    [ 7.500, 10.000) = 168 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.375 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      8.307 ms/op
     p(99.9900) =     15.767 ms/op
     p(99.9990) =     21.508 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 4.194 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.475 ms/op
                 getUser·p0.9999: 22.315 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   2: 3.055 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.988 ms/op
                 getUser·p0.9999: 14.172 ms/op
                 getUser·p1.00:   14.434 ms/op

Iteration   3: 3.003 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.811 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.783 ms/op
                 getUser·p0.9999: 18.483 ms/op
                 getUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316910
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21569 
    [ 2.500,  5.000) = 294205 
    [ 5.000,  7.500) = 884 
    [ 7.500, 10.000) = 60 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.054 ms/op
     p(99.9900) =     20.861 ms/op
     p(99.9990) =     22.348 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 4.526 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.096 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 3.930 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.647 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.084 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   2: 3.934 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.141 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  14.834 ms/op
                 listUser·p0.9999: 17.432 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.959 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.272 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.844 ms/op
                 listUser·p0.999:  15.127 ms/op
                 listUser·p0.9999: 20.018 ms/op
                 listUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243652
  mean =      3.941 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2933 
    [ 2.500,  5.000) = 218964 
    [ 5.000,  7.500) = 20679 
    [ 7.500, 10.000) = 621 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 191 
    [15.000, 17.500) = 125 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.882 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.352 ms/op
     p(99.9900) =     19.497 ms/op
     p(99.9990) =     20.719 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.522 ± 4.145  ops/ms
ClientGrpc.existUser                       thrpt       3  11.195 ± 1.561  ops/ms
ClientGrpc.getUser                         thrpt       3  10.650 ± 0.298  ops/ms
ClientGrpc.listUser                        thrpt       3   8.040 ± 1.219  ops/ms
ClientGrpc.createUser                       avgt       3   3.011 ± 0.715   ms/op
ClientGrpc.existUser                        avgt       3   2.870 ± 0.149   ms/op
ClientGrpc.getUser                          avgt       3   2.993 ± 0.311   ms/op
ClientGrpc.listUser                         avgt       3   3.903 ± 0.689   ms/op
ClientGrpc.createUser                     sample  318301   3.017 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.743           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.536           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.476           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.743           ms/op
ClientGrpc.existUser                      sample  331717   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.752           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.375           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.767           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.627           ms/op
ClientGrpc.getUser                        sample  316910   3.029 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.746           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.002           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.054           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.861           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.348           ms/op
ClientGrpc.listUser                       sample  243652   3.941 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.141           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.785           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.352           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.497           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.398           ms/op
