# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.070 ops/ms
# Warmup Iteration   2: 8.958 ops/ms
# Warmup Iteration   3: 9.738 ops/ms
Iteration   1: 10.177 ops/ms
Iteration   2: 10.580 ops/ms
Iteration   3: 10.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.365 ±(99.9%) 3.697 ops/ms [Average]
  (min, avg, max) = (10.177, 10.365, 10.580), stdev = 0.203
  CI (99.9%): [6.668, 14.062] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 6.840 ops/ms
# Warmup Iteration   2: 10.229 ops/ms
# Warmup Iteration   3: 10.874 ops/ms
Iteration   1: 10.825 ops/ms
Iteration   2: 11.010 ops/ms
Iteration   3: 11.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.948 ±(99.9%) 1.948 ops/ms [Average]
  (min, avg, max) = (10.825, 10.948, 11.010), stdev = 0.107
  CI (99.9%): [9.000, 12.896] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.337 ops/ms
# Warmup Iteration   2: 9.772 ops/ms
# Warmup Iteration   3: 10.290 ops/ms
Iteration   1: 10.524 ops/ms
Iteration   2: 10.426 ops/ms
Iteration   3: 10.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.442 ±(99.9%) 1.368 ops/ms [Average]
  (min, avg, max) = (10.377, 10.442, 10.524), stdev = 0.075
  CI (99.9%): [9.075, 11.810] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 4.911 ops/ms
# Warmup Iteration   2: 7.369 ops/ms
# Warmup Iteration   3: 7.706 ops/ms
Iteration   1: 7.985 ops/ms
Iteration   2: 7.968 ops/ms
Iteration   3: 7.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.958 ±(99.9%) 0.606 ops/ms [Average]
  (min, avg, max) = (7.921, 7.958, 7.985), stdev = 0.033
  CI (99.9%): [7.352, 8.564] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.666 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.003 ms/op
Iteration   1: 3.065 ±(99.9%) 0.004 ms/op
Iteration   2: 3.086 ±(99.9%) 0.002 ms/op
Iteration   3: 3.085 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.079 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (3.065, 3.079, 3.086), stdev = 0.012
  CI (99.9%): [2.862, 3.295] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.748 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.971 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.855 ±(99.9%) 0.003 ms/op
Iteration   1: 2.893 ±(99.9%) 0.003 ms/op
Iteration   2: 2.954 ±(99.9%) 0.002 ms/op
Iteration   3: 2.868 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.905 ±(99.9%) 0.806 ms/op [Average]
  (min, avg, max) = (2.868, 2.905, 2.954), stdev = 0.044
  CI (99.9%): [2.099, 3.711] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.158 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.088 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.965 ±(99.9%) 0.003 ms/op
Iteration   1: 3.027 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
Iteration   3: 2.995 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.005 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (2.993, 3.005, 3.027), stdev = 0.019
  CI (99.9%): [2.657, 3.352] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.898 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.036 ±(99.9%) 0.016 ms/op
Iteration   1: 4.118 ±(99.9%) 0.019 ms/op
Iteration   2: 4.077 ±(99.9%) 0.025 ms/op
Iteration   3: 4.010 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.068 ±(99.9%) 0.999 ms/op [Average]
  (min, avg, max) = (4.010, 4.068, 4.118), stdev = 0.055
  CI (99.9%): [3.069, 5.067] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.255 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.026 ±(99.9%) 0.007 ms/op
Iteration   1: 3.009 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  7.436 ms/op
                 createUser·p0.9999: 18.362 ms/op
                 createUser·p1.00:   18.645 ms/op

Iteration   2: 3.032 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.944 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.189 ms/op
                 createUser·p0.9999: 14.254 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   3: 2.964 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.793 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  9.912 ms/op
                 createUser·p0.9999: 17.055 ms/op
                 createUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319663
  mean =      3.001 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 867 
    [ 1.250,  2.500) = 32095 
    [ 2.500,  3.750) = 269797 
    [ 3.750,  5.000) = 15376 
    [ 5.000,  6.250) = 768 
    [ 6.250,  7.500) = 357 
    [ 7.500,  8.750) = 118 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 35 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 47 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.440 ms/op
     p(99.9000) =      8.170 ms/op
     p(99.9900) =     17.992 ms/op
     p(99.9990) =     18.481 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.067 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.817 ±(99.9%) 0.006 ms/op
Iteration   1: 2.793 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  6.648 ms/op
                 existUser·p0.9999: 12.206 ms/op
                 existUser·p1.00:   12.616 ms/op

Iteration   2: 2.917 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.859 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.432 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  6.226 ms/op
                 existUser·p0.9999: 14.942 ms/op
                 existUser·p1.00:   15.057 ms/op

Iteration   3: 2.921 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   3.874 ms/op
                 existUser·p0.999:  6.467 ms/op
                 existUser·p0.9999: 26.314 ms/op
                 existUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333691
  mean =      2.876 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38256 
    [ 2.500,  5.000) = 294731 
    [ 5.000,  7.500) = 508 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.441 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      6.523 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     27.012 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.347 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.316 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.512 ms/op
                 getUser·p0.999:  7.561 ms/op
                 getUser·p0.9999: 17.113 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.785 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.566 ms/op
                 getUser·p0.9999: 29.327 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.718 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  7.946 ms/op
                 getUser·p0.9999: 19.677 ms/op
                 getUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314493
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20157 
    [ 2.500,  5.000) = 292947 
    [ 5.000,  7.500) = 1060 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.586 ms/op
     p(99.9900) =     27.740 ms/op
     p(99.9990) =     29.842 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.915 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.347 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.947 ±(99.9%) 0.011 ms/op
Iteration   1: 3.996 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.270 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  14.689 ms/op
                 listUser·p0.9999: 18.709 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 4.064 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.174 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.104 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  16.335 ms/op
                 listUser·p0.9999: 26.219 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   3: 4.010 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  20.160 ms/op
                 listUser·p0.9999: 25.868 ms/op
                 listUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238629
  mean =      4.023 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3469 
    [ 2.500,  5.000) = 211396 
    [ 5.000,  7.500) = 22373 
    [ 7.500, 10.000) = 909 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.045 ms/op
     p(99.9000) =     16.187 ms/op
     p(99.9900) =     25.854 ms/op
     p(99.9990) =     27.827 ms/op
     p(99.9999) =     27.918 ms/op
    p(100.0000) =     27.918 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.365 ± 3.697  ops/ms
ClientGrpc.existUser                       thrpt       3  10.948 ± 1.948  ops/ms
ClientGrpc.getUser                         thrpt       3  10.442 ± 1.368  ops/ms
ClientGrpc.listUser                        thrpt       3   7.958 ± 0.606  ops/ms
ClientGrpc.createUser                       avgt       3   3.079 ± 0.217   ms/op
ClientGrpc.existUser                        avgt       3   2.905 ± 0.806   ms/op
ClientGrpc.getUser                          avgt       3   3.005 ± 0.347   ms/op
ClientGrpc.listUser                         avgt       3   4.068 ± 0.999   ms/op
ClientGrpc.createUser                     sample  319663   3.001 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.793           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.170           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.992           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.645           ms/op
ClientGrpc.existUser                      sample  333691   2.876 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.726           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.884           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.285           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.441           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.523           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.826           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.066           ms/op
ClientGrpc.getUser                        sample  314493   3.052 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.718           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.586           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.740           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.983           ms/op
ClientGrpc.listUser                       sample  238629   4.023 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.910           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.997           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.187           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.854           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.918           ms/op
