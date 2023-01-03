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
# Warmup Iteration   1: 4.974 ops/ms
# Warmup Iteration   2: 9.572 ops/ms
# Warmup Iteration   3: 10.667 ops/ms
Iteration   1: 10.404 ops/ms
Iteration   2: 10.320 ops/ms
Iteration   3: 10.413 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.379 ±(99.9%) 0.936 ops/ms [Average]
  (min, avg, max) = (10.320, 10.379, 10.413), stdev = 0.051
  CI (99.9%): [9.443, 11.315] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.238 ops/ms
# Warmup Iteration   2: 10.875 ops/ms
# Warmup Iteration   3: 10.756 ops/ms
Iteration   1: 10.993 ops/ms
Iteration   2: 10.910 ops/ms
Iteration   3: 10.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.860 ±(99.9%) 3.003 ops/ms [Average]
  (min, avg, max) = (10.676, 10.860, 10.993), stdev = 0.165
  CI (99.9%): [7.857, 13.863] (assumes normal distribution)


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
# Warmup Iteration   1: 7.336 ops/ms
# Warmup Iteration   2: 10.274 ops/ms
# Warmup Iteration   3: 10.629 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.400 ops/ms
Iteration   3: 10.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.542 ±(99.9%) 2.426 ops/ms [Average]
  (min, avg, max) = (10.400, 10.542, 10.664), stdev = 0.133
  CI (99.9%): [8.117, 12.968] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.043 ops/ms
# Warmup Iteration   2: 7.900 ops/ms
# Warmup Iteration   3: 7.972 ops/ms
Iteration   1: 8.189 ops/ms
Iteration   2: 8.230 ops/ms
Iteration   3: 8.081 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.166 ±(99.9%) 1.405 ops/ms [Average]
  (min, avg, max) = (8.081, 8.166, 8.230), stdev = 0.077
  CI (99.9%): [6.762, 9.571] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.998 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.003 ms/op
Iteration   1: 3.058 ±(99.9%) 0.002 ms/op
Iteration   2: 3.070 ±(99.9%) 0.002 ms/op
Iteration   3: 3.140 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.089 ±(99.9%) 0.809 ms/op [Average]
  (min, avg, max) = (3.058, 3.089, 3.140), stdev = 0.044
  CI (99.9%): [2.280, 3.898] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.641 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.884 ±(99.9%) 0.004 ms/op
Iteration   1: 2.870 ±(99.9%) 0.002 ms/op
Iteration   2: 2.904 ±(99.9%) 0.003 ms/op
Iteration   3: 2.956 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.910 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (2.870, 2.910, 2.956), stdev = 0.043
  CI (99.9%): [2.116, 3.703] (assumes normal distribution)


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
# Warmup Iteration   1: 4.017 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.002 ms/op
Iteration   1: 3.019 ±(99.9%) 0.002 ms/op
Iteration   2: 3.110 ±(99.9%) 0.001 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (3.019, 3.062, 3.110), stdev = 0.045
  CI (99.9%): [2.236, 3.888] (assumes normal distribution)


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
# Warmup Iteration   1: 4.765 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.089 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.007 ms/op
Iteration   1: 4.066 ±(99.9%) 0.031 ms/op
Iteration   2: 3.914 ±(99.9%) 0.033 ms/op
Iteration   3: 3.897 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.959 ±(99.9%) 1.706 ms/op [Average]
  (min, avg, max) = (3.897, 3.959, 4.066), stdev = 0.094
  CI (99.9%): [2.253, 5.665] (assumes normal distribution)


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
# Warmup Iteration   1: 4.046 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
Iteration   1: 3.096 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.467 ms/op
                 createUser·p0.999:  9.796 ms/op
                 createUser·p0.9999: 15.647 ms/op
                 createUser·p1.00:   16.122 ms/op

Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.769 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  7.758 ms/op
                 createUser·p0.9999: 20.127 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.022 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.331 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.141 ms/op
                 createUser·p0.999:  10.372 ms/op
                 createUser·p0.9999: 26.771 ms/op
                 createUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313183
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29235 
    [ 2.500,  5.000) = 282794 
    [ 5.000,  7.500) = 583 
    [ 7.500, 10.000) = 254 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.331 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =     10.060 ms/op
     p(99.9900) =     26.270 ms/op
     p(99.9990) =     26.964 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 3.652 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.931 ±(99.9%) 0.006 ms/op
Iteration   1: 2.935 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.641 ms/op
                 existUser·p0.95:   3.813 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  5.620 ms/op
                 existUser·p0.9999: 12.093 ms/op
                 existUser·p1.00:   12.354 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.491 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  6.275 ms/op
                 existUser·p0.9999: 17.077 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   3: 2.927 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.116 ms/op
                 existUser·p0.9999: 14.369 ms/op
                 existUser·p1.00:   15.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326738
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2090 
    [ 1.250,  2.500) = 52609 
    [ 2.500,  3.750) = 254345 
    [ 3.750,  5.000) = 16849 
    [ 5.000,  6.250) = 509 
    [ 6.250,  7.500) = 131 
    [ 7.500,  8.750) = 20 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.491 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      6.267 ms/op
     p(99.9900) =     15.581 ms/op
     p(99.9990) =     17.448 ms/op
     p(99.9999) =     17.564 ms/op
    p(100.0000) =     17.564 ms/op


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
# Warmup Iteration   1: 3.805 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.007 ms/op
Iteration   1: 3.154 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  6.017 ms/op
                 getUser·p0.9999: 13.577 ms/op
                 getUser·p1.00:   13.844 ms/op

Iteration   2: 3.164 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.431 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.497 ms/op
                 getUser·p0.9999: 14.006 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   3: 3.196 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.039 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.003 ms/op
                 getUser·p0.9999: 18.841 ms/op
                 getUser·p1.00:   19.104 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302782
  mean =      3.171 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 867 
    [ 1.250,  2.500) = 19015 
    [ 2.500,  3.750) = 242713 
    [ 3.750,  5.000) = 39200 
    [ 5.000,  6.250) = 389 
    [ 6.250,  7.500) = 257 
    [ 7.500,  8.750) = 104 
    [ 8.750, 10.000) = 44 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.431 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.791 ms/op
     p(99.9900) =     18.355 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.104 ms/op
    p(100.0000) =     19.104 ms/op


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
# Warmup Iteration   1: 5.251 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
Iteration   1: 4.028 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  12.354 ms/op
                 listUser·p0.9999: 13.533 ms/op
                 listUser·p1.00:   13.926 ms/op

Iteration   2: 3.928 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.565 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.505 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  17.308 ms/op
                 listUser·p0.9999: 22.863 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 3.904 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.507 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.504 ms/op
                 listUser·p0.9999: 20.827 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243025
  mean =      3.953 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3685 
    [ 2.500,  5.000) = 212111 
    [ 5.000,  7.500) = 25992 
    [ 7.500, 10.000) = 725 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 151 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     22.403 ms/op
     p(99.9990) =     23.317 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.379 ± 0.936  ops/ms
ClientGrpc.existUser                       thrpt       3  10.860 ± 3.003  ops/ms
ClientGrpc.getUser                         thrpt       3  10.542 ± 2.426  ops/ms
ClientGrpc.listUser                        thrpt       3   8.166 ± 1.405  ops/ms
ClientGrpc.createUser                       avgt       3   3.089 ± 0.809   ms/op
ClientGrpc.existUser                        avgt       3   2.910 ± 0.793   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 0.826   ms/op
ClientGrpc.listUser                         avgt       3   3.959 ± 1.706   ms/op
ClientGrpc.createUser                     sample  313183   3.066 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.331           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.887           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.060           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.270           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.066           ms/op
ClientGrpc.existUser                      sample  326738   2.938 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.491           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.768           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.267           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.581           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.564           ms/op
ClientGrpc.getUser                        sample  302782   3.171 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.431           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.998           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.325           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.791           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.355           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.104           ms/op
ClientGrpc.listUser                       sample  243025   3.953 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.507           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.513           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.484           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.403           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.331           ms/op
