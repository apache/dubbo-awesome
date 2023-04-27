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
# Warmup Iteration   1: 3.979 ops/ms
# Warmup Iteration   2: 8.767 ops/ms
# Warmup Iteration   3: 9.885 ops/ms
Iteration   1: 10.125 ops/ms
Iteration   2: 10.267 ops/ms
Iteration   3: 10.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.283 ±(99.9%) 3.051 ops/ms [Average]
  (min, avg, max) = (10.125, 10.283, 10.458), stdev = 0.167
  CI (99.9%): [7.233, 13.334] (assumes normal distribution)


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
# Warmup Iteration   1: 7.246 ops/ms
# Warmup Iteration   2: 10.371 ops/ms
# Warmup Iteration   3: 10.773 ops/ms
Iteration   1: 10.791 ops/ms
Iteration   2: 10.971 ops/ms
Iteration   3: 11.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.946 ±(99.9%) 2.633 ops/ms [Average]
  (min, avg, max) = (10.791, 10.946, 11.077), stdev = 0.144
  CI (99.9%): [8.313, 13.579] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.014 ops/ms
# Warmup Iteration   2: 9.503 ops/ms
# Warmup Iteration   3: 10.242 ops/ms
Iteration   1: 10.227 ops/ms
Iteration   2: 10.482 ops/ms
Iteration   3: 10.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.380 ±(99.9%) 2.460 ops/ms [Average]
  (min, avg, max) = (10.227, 10.380, 10.482), stdev = 0.135
  CI (99.9%): [7.920, 12.840] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.595 ops/ms
# Warmup Iteration   2: 7.681 ops/ms
# Warmup Iteration   3: 7.785 ops/ms
Iteration   1: 8.144 ops/ms
Iteration   2: 8.363 ops/ms
Iteration   3: 7.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.162 ±(99.9%) 3.523 ops/ms [Average]
  (min, avg, max) = (7.978, 8.162, 8.363), stdev = 0.193
  CI (99.9%): [4.639, 11.684] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.135 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.076 ±(99.9%) 0.004 ms/op
Iteration   1: 3.033 ±(99.9%) 0.009 ms/op
Iteration   2: 3.050 ±(99.9%) 0.003 ms/op
Iteration   3: 3.065 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.049 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (3.033, 3.049, 3.065), stdev = 0.016
  CI (99.9%): [2.758, 3.341] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.138 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.002 ms/op
Iteration   1: 2.961 ±(99.9%) 0.002 ms/op
Iteration   2: 2.939 ±(99.9%) 0.004 ms/op
Iteration   3: 2.982 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.960 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (2.939, 2.960, 2.982), stdev = 0.021
  CI (99.9%): [2.571, 3.350] (assumes normal distribution)


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.143 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.003 ms/op
Iteration   1: 3.076 ±(99.9%) 0.002 ms/op
Iteration   2: 3.083 ±(99.9%) 0.002 ms/op
Iteration   3: 3.080 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.080 ±(99.9%) 0.069 ms/op [Average]
  (min, avg, max) = (3.076, 3.080, 3.083), stdev = 0.004
  CI (99.9%): [3.010, 3.149] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.362 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.068 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.013 ms/op
Iteration   1: 3.957 ±(99.9%) 0.010 ms/op
Iteration   2: 3.952 ±(99.9%) 0.010 ms/op
Iteration   3: 3.959 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.956 ±(99.9%) 0.066 ms/op [Average]
  (min, avg, max) = (3.952, 3.956, 3.959), stdev = 0.004
  CI (99.9%): [3.890, 4.022] (assumes normal distribution)


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.762 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  6.777 ms/op
                 createUser·p0.9999: 15.258 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  9.455 ms/op
                 createUser·p0.9999: 14.757 ms/op
                 createUser·p1.00:   15.843 ms/op

Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.449 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  7.965 ms/op
                 createUser·p0.9999: 17.582 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313164
  mean =      3.065 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 372 
    [ 1.250,  2.500) = 14844 
    [ 2.500,  3.750) = 282234 
    [ 3.750,  5.000) = 13986 
    [ 5.000,  6.250) = 1033 
    [ 6.250,  7.500) = 342 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      7.847 ms/op
     p(99.9900) =     15.838 ms/op
     p(99.9990) =     17.940 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 4.003 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.006 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  7.219 ms/op
                 existUser·p0.9999: 13.521 ms/op
                 existUser·p1.00:   14.909 ms/op

Iteration   2: 2.912 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  5.896 ms/op
                 existUser·p0.9999: 15.025 ms/op
                 existUser·p1.00:   15.696 ms/op

Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.846 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.386 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  6.498 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327332
  mean =      2.930 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35853 
    [ 2.500,  5.000) = 290485 
    [ 5.000,  7.500) = 808 
    [ 7.500, 10.000) = 26 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.904 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      6.627 ms/op
     p(99.9900) =     19.333 ms/op
     p(99.9990) =     26.771 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.006 ms/op
Iteration   1: 3.117 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.666 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  7.851 ms/op
                 getUser·p0.9999: 18.800 ms/op
                 getUser·p1.00:   19.366 ms/op

Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.457 ms/op
                 getUser·p0.999:  7.919 ms/op
                 getUser·p0.9999: 19.169 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   3: 3.075 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.558 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  7.127 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309844
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13629 
    [ 2.500,  5.000) = 294948 
    [ 5.000,  7.500) = 914 
    [ 7.500, 10.000) = 161 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     18.809 ms/op
     p(99.9990) =     19.671 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 5.154 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.975 ±(99.9%) 0.012 ms/op
Iteration   1: 3.924 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.399 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  15.556 ms/op
                 listUser·p0.9999: 21.284 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 4.000 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.516 ms/op
                 listUser·p0.9999: 23.757 ms/op
                 listUser·p1.00:   24.379 ms/op

Iteration   3: 3.975 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 16.971 ms/op
                 listUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242024
  mean =      3.966 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2285 
    [ 2.500,  5.000) = 218717 
    [ 5.000,  7.500) = 19834 
    [ 7.500, 10.000) = 677 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     15.122 ms/op
     p(99.9900) =     22.793 ms/op
     p(99.9990) =     24.198 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.283 ± 3.051  ops/ms
ClientGrpc.existUser                       thrpt       3  10.946 ± 2.633  ops/ms
ClientGrpc.getUser                         thrpt       3  10.380 ± 2.460  ops/ms
ClientGrpc.listUser                        thrpt       3   8.162 ± 3.523  ops/ms
ClientGrpc.createUser                       avgt       3   3.049 ± 0.291   ms/op
ClientGrpc.existUser                        avgt       3   2.960 ± 0.390   ms/op
ClientGrpc.getUser                          avgt       3   3.080 ± 0.069   ms/op
ClientGrpc.listUser                         avgt       3   3.956 ± 0.066   ms/op
ClientGrpc.createUser                     sample  313164   3.065 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.581           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.530           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.847           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.838           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.121           ms/op
ClientGrpc.existUser                      sample  327332   2.930 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.729           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.904           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.627           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.333           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.935           ms/op
ClientGrpc.getUser                        sample  309844   3.096 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.558           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.668           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.809           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.087           ms/op
ClientGrpc.listUser                       sample  242024   3.966 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.100           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.122           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.793           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.379           ms/op
