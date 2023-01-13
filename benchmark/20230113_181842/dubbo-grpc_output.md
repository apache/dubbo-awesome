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
# Warmup Iteration   1: 4.752 ops/ms
# Warmup Iteration   2: 9.462 ops/ms
# Warmup Iteration   3: 10.260 ops/ms
Iteration   1: 10.921 ops/ms
Iteration   2: 10.677 ops/ms
Iteration   3: 10.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.633 ±(99.9%) 5.690 ops/ms [Average]
  (min, avg, max) = (10.302, 10.633, 10.921), stdev = 0.312
  CI (99.9%): [4.943, 16.324] (assumes normal distribution)


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
# Warmup Iteration   1: 8.036 ops/ms
# Warmup Iteration   2: 11.103 ops/ms
# Warmup Iteration   3: 10.842 ops/ms
Iteration   1: 11.450 ops/ms
Iteration   2: 10.821 ops/ms
Iteration   3: 10.958 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.076 ±(99.9%) 6.040 ops/ms [Average]
  (min, avg, max) = (10.821, 11.076, 11.450), stdev = 0.331
  CI (99.9%): [5.036, 17.117] (assumes normal distribution)


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
# Warmup Iteration   1: 7.930 ops/ms
# Warmup Iteration   2: 10.473 ops/ms
# Warmup Iteration   3: 10.717 ops/ms
Iteration   1: 10.379 ops/ms
Iteration   2: 10.406 ops/ms
Iteration   3: 10.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.387 ±(99.9%) 0.312 ops/ms [Average]
  (min, avg, max) = (10.374, 10.387, 10.406), stdev = 0.017
  CI (99.9%): [10.075, 10.699] (assumes normal distribution)


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
# Warmup Iteration   1: 7.002 ops/ms
# Warmup Iteration   2: 7.581 ops/ms
# Warmup Iteration   3: 7.859 ops/ms
Iteration   1: 7.833 ops/ms
Iteration   2: 7.704 ops/ms
Iteration   3: 8.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.952 ±(99.9%) 5.900 ops/ms [Average]
  (min, avg, max) = (7.704, 7.952, 8.317), stdev = 0.323
  CI (99.9%): [2.052, 13.851] (assumes normal distribution)


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.003 ms/op
Iteration   1: 3.146 ±(99.9%) 0.002 ms/op
Iteration   2: 3.164 ±(99.9%) 0.001 ms/op
Iteration   3: 3.188 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.166 ±(99.9%) 0.383 ms/op [Average]
  (min, avg, max) = (3.146, 3.166, 3.188), stdev = 0.021
  CI (99.9%): [2.783, 3.548] (assumes normal distribution)


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
# Warmup Iteration   1: 3.754 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.002 ms/op
Iteration   1: 2.935 ±(99.9%) 0.003 ms/op
Iteration   2: 2.895 ±(99.9%) 0.003 ms/op
Iteration   3: 2.957 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.929 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (2.895, 2.929, 2.957), stdev = 0.031
  CI (99.9%): [2.355, 3.504] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.108 ±(99.9%) 0.002 ms/op
Iteration   1: 2.967 ±(99.9%) 0.002 ms/op
Iteration   2: 3.079 ±(99.9%) 0.002 ms/op
Iteration   3: 3.020 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.022 ±(99.9%) 1.025 ms/op [Average]
  (min, avg, max) = (2.967, 3.022, 3.079), stdev = 0.056
  CI (99.9%): [1.997, 4.046] (assumes normal distribution)


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
# Warmup Iteration   1: 5.148 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.027 ms/op
Iteration   1: 4.081 ±(99.9%) 0.010 ms/op
Iteration   2: 4.070 ±(99.9%) 0.009 ms/op
Iteration   3: 4.009 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.053 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (4.009, 4.053, 4.081), stdev = 0.039
  CI (99.9%): [3.340, 4.766] (assumes normal distribution)


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.054 ±(99.9%) 0.006 ms/op
Iteration   1: 2.955 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.387 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.302 ms/op
                 createUser·p0.9999: 12.700 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   2: 2.994 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.515 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.793 ms/op
                 createUser·p0.99:   4.145 ms/op
                 createUser·p0.999:  10.878 ms/op
                 createUser·p0.9999: 16.230 ms/op
                 createUser·p1.00:   16.564 ms/op

Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.307 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.650 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.832 ms/op
                 createUser·p0.9999: 14.208 ms/op
                 createUser·p1.00:   14.516 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323375
  mean =      2.970 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3877 
    [ 1.250,  2.500) = 27129 
    [ 2.500,  3.750) = 279410 
    [ 3.750,  5.000) = 11846 
    [ 5.000,  6.250) = 476 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      9.333 ms/op
     p(99.9900) =     15.308 ms/op
     p(99.9990) =     16.475 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.006 ms/op
Iteration   1: 2.958 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.356 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  7.753 ms/op
                 existUser·p0.9999: 13.605 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.770 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.029 ms/op
                 existUser·p0.9999: 22.610 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 2.992 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.655 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  8.724 ms/op
                 existUser·p0.9999: 17.617 ms/op
                 existUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 322916
  mean =      2.972 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45360 
    [ 2.500,  5.000) = 276629 
    [ 5.000,  7.500) = 592 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      7.603 ms/op
     p(99.9900) =     20.555 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.104 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.006 ms/op
Iteration   1: 2.933 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.391 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.543 ms/op
                 getUser·p0.99:   4.273 ms/op
                 getUser·p0.999:  7.226 ms/op
                 getUser·p0.9999: 12.322 ms/op
                 getUser·p1.00:   12.796 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.685 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  6.238 ms/op
                 getUser·p0.9999: 13.032 ms/op
                 getUser·p1.00:   13.697 ms/op

Iteration   3: 2.963 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.421 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  6.332 ms/op
                 getUser·p0.9999: 14.339 ms/op
                 getUser·p1.00:   15.286 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323799
  mean =      2.967 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3076 
    [ 1.250,  2.500) = 31010 
    [ 2.500,  3.750) = 275203 
    [ 3.750,  5.000) = 13620 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 130 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 2 
    [10.000, 11.250) = 18 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.419 ms/op
     p(99.9900) =     13.918 ms/op
     p(99.9990) =     15.041 ms/op
     p(99.9999) =     15.286 ms/op
    p(100.0000) =     15.286 ms/op


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
# Warmup Iteration   1: 5.070 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.092 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.012 ms/op
Iteration   1: 4.123 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.886 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  14.542 ms/op
                 listUser·p0.9999: 21.749 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   2: 3.969 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.764 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.067 ms/op
                 listUser·p0.999:  14.292 ms/op
                 listUser·p0.9999: 18.084 ms/op
                 listUser·p1.00:   18.350 ms/op

Iteration   3: 4.126 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.805 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  15.445 ms/op
                 listUser·p0.9999: 22.134 ms/op
                 listUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235751
  mean =      4.071 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4842 
    [ 2.500,  5.000) = 193704 
    [ 5.000,  7.500) = 35640 
    [ 7.500, 10.000) = 1035 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.710 ms/op
     p(99.0000) =      7.131 ms/op
     p(99.9000) =     14.488 ms/op
     p(99.9900) =     21.674 ms/op
     p(99.9990) =     26.629 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.633 ± 5.690  ops/ms
ClientGrpc.existUser                       thrpt       3  11.076 ± 6.040  ops/ms
ClientGrpc.getUser                         thrpt       3  10.387 ± 0.312  ops/ms
ClientGrpc.listUser                        thrpt       3   7.952 ± 5.900  ops/ms
ClientGrpc.createUser                       avgt       3   3.166 ± 0.383   ms/op
ClientGrpc.existUser                        avgt       3   2.929 ± 0.574   ms/op
ClientGrpc.getUser                          avgt       3   3.022 ± 1.025   ms/op
ClientGrpc.listUser                         avgt       3   4.053 ± 0.713   ms/op
ClientGrpc.createUser                     sample  323375   2.970 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.307           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.002           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.445           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.333           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.308           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.564           ms/op
ClientGrpc.existUser                      sample  322916   2.972 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.356           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.813           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.603           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.555           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.265           ms/op
ClientGrpc.getUser                        sample  323799   2.967 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.391           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.478           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.419           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.918           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.286           ms/op
ClientGrpc.listUser                       sample  235751   4.071 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.764           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.131           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.488           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.674           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.739           ms/op
