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
# Warmup Iteration   1: 4.755 ops/ms
# Warmup Iteration   2: 9.368 ops/ms
# Warmup Iteration   3: 10.226 ops/ms
Iteration   1: 10.691 ops/ms
Iteration   2: 11.159 ops/ms
Iteration   3: 10.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.885 ±(99.9%) 4.456 ops/ms [Average]
  (min, avg, max) = (10.691, 10.885, 11.159), stdev = 0.244
  CI (99.9%): [6.429, 15.341] (assumes normal distribution)


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
# Warmup Iteration   1: 8.036 ops/ms
# Warmup Iteration   2: 10.934 ops/ms
# Warmup Iteration   3: 11.297 ops/ms
Iteration   1: 11.574 ops/ms
Iteration   2: 11.167 ops/ms
Iteration   3: 11.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.363 ±(99.9%) 3.721 ops/ms [Average]
  (min, avg, max) = (11.167, 11.363, 11.574), stdev = 0.204
  CI (99.9%): [7.642, 15.084] (assumes normal distribution)


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
# Warmup Iteration   1: 8.773 ops/ms
# Warmup Iteration   2: 10.493 ops/ms
# Warmup Iteration   3: 10.871 ops/ms
Iteration   1: 10.784 ops/ms
Iteration   2: 10.567 ops/ms
Iteration   3: 10.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.747 ±(99.9%) 2.998 ops/ms [Average]
  (min, avg, max) = (10.567, 10.747, 10.890), stdev = 0.164
  CI (99.9%): [7.749, 13.745] (assumes normal distribution)


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
# Warmup Iteration   1: 5.662 ops/ms
# Warmup Iteration   2: 8.000 ops/ms
# Warmup Iteration   3: 8.331 ops/ms
Iteration   1: 8.326 ops/ms
Iteration   2: 8.755 ops/ms
Iteration   3: 8.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.476 ±(99.9%) 4.420 ops/ms [Average]
  (min, avg, max) = (8.326, 8.476, 8.755), stdev = 0.242
  CI (99.9%): [4.055, 12.896] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.004 ms/op
Iteration   1: 2.954 ±(99.9%) 0.003 ms/op
Iteration   2: 2.956 ±(99.9%) 0.004 ms/op
Iteration   3: 2.951 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.954 ±(99.9%) 0.043 ms/op [Average]
  (min, avg, max) = (2.951, 2.954, 2.956), stdev = 0.002
  CI (99.9%): [2.911, 2.996] (assumes normal distribution)


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.937 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.818 ±(99.9%) 0.003 ms/op
Iteration   1: 2.822 ±(99.9%) 0.003 ms/op
Iteration   2: 2.804 ±(99.9%) 0.003 ms/op
Iteration   3: 2.839 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.822 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (2.804, 2.822, 2.839), stdev = 0.017
  CI (99.9%): [2.503, 3.141] (assumes normal distribution)


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
# Warmup Iteration   1: 3.637 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.003 ms/op
Iteration   1: 2.922 ±(99.9%) 0.002 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 2.925 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.932 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (2.922, 2.932, 2.949), stdev = 0.015
  CI (99.9%): [2.666, 3.198] (assumes normal distribution)


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.850 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.886 ±(99.9%) 0.035 ms/op
Iteration   1: 3.781 ±(99.9%) 0.012 ms/op
Iteration   2: 3.765 ±(99.9%) 0.025 ms/op
Iteration   3: 3.687 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.744 ±(99.9%) 0.916 ms/op [Average]
  (min, avg, max) = (3.687, 3.744, 3.781), stdev = 0.050
  CI (99.9%): [2.829, 4.660] (assumes normal distribution)


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
# Warmup Iteration   1: 3.502 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 2.941 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.520 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  8.722 ms/op
                 createUser·p0.9999: 13.615 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   2: 2.955 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  13.124 ms/op
                 createUser·p0.9999: 17.236 ms/op
                 createUser·p1.00:   18.448 ms/op

Iteration   3: 2.982 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.474 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  6.721 ms/op
                 createUser·p0.9999: 23.765 ms/op
                 createUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 324381
  mean =      2.959 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41597 
    [ 2.500,  5.000) = 281172 
    [ 5.000,  7.500) = 1106 
    [ 7.500, 10.000) = 151 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     11.381 ms/op
     p(99.9900) =     21.096 ms/op
     p(99.9990) =     24.830 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.909 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.868 ±(99.9%) 0.005 ms/op
Iteration   1: 2.811 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.379 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.325 ms/op
                 existUser·p0.9999: 17.210 ms/op
                 existUser·p1.00:   17.564 ms/op

Iteration   2: 2.846 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.527 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  5.895 ms/op
                 existUser·p0.9999: 20.323 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   3: 2.765 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.474 ms/op
                 existUser·p0.50:   2.793 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.523 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  6.734 ms/op
                 existUser·p0.9999: 15.015 ms/op
                 existUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 341926
  mean =      2.807 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67184 
    [ 2.500,  5.000) = 273765 
    [ 5.000,  7.500) = 744 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.379 ms/op
     p(50.0000) =      2.802 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.259 ms/op
     p(99.9900) =     17.557 ms/op
     p(99.9990) =     20.794 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.886 ±(99.9%) 0.007 ms/op
Iteration   1: 2.919 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   2.929 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   4.137 ms/op
                 getUser·p0.999:  6.291 ms/op
                 getUser·p0.9999: 12.749 ms/op
                 getUser·p1.00:   13.222 ms/op

Iteration   2: 2.989 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  6.980 ms/op
                 getUser·p0.9999: 14.816 ms/op
                 getUser·p1.00:   15.827 ms/op

Iteration   3: 2.968 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.702 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  7.960 ms/op
                 getUser·p0.9999: 16.350 ms/op
                 getUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324164
  mean =      2.958 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1682 
    [ 1.250,  2.500) = 26573 
    [ 2.500,  3.750) = 284034 
    [ 3.750,  5.000) = 10904 
    [ 5.000,  6.250) = 506 
    [ 6.250,  7.500) = 229 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 20 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 80 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 12 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      6.668 ms/op
     p(99.9900) =     15.158 ms/op
     p(99.9990) =     17.056 ms/op
     p(99.9999) =     17.170 ms/op
    p(100.0000) =     17.170 ms/op


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
# Warmup Iteration   1: 5.029 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.011 ms/op
Iteration   1: 3.846 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  13.151 ms/op
                 listUser·p0.9999: 15.610 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 3.867 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.092 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  17.400 ms/op
                 listUser·p0.9999: 21.839 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   3: 3.817 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.090 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  15.015 ms/op
                 listUser·p0.9999: 22.630 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249652
  mean =      3.843 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6466 
    [ 2.500,  5.000) = 221727 
    [ 5.000,  7.500) = 20249 
    [ 7.500, 10.000) = 665 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.090 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     14.434 ms/op
     p(99.9900) =     22.185 ms/op
     p(99.9990) =     22.790 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.885 ± 4.456  ops/ms
ClientGrpc.existUser                       thrpt       3  11.363 ± 3.721  ops/ms
ClientGrpc.getUser                         thrpt       3  10.747 ± 2.998  ops/ms
ClientGrpc.listUser                        thrpt       3   8.476 ± 4.420  ops/ms
ClientGrpc.createUser                       avgt       3   2.954 ± 0.043   ms/op
ClientGrpc.existUser                        avgt       3   2.822 ± 0.319   ms/op
ClientGrpc.getUser                          avgt       3   2.932 ± 0.266   ms/op
ClientGrpc.listUser                         avgt       3   3.744 ± 0.916   ms/op
ClientGrpc.createUser                     sample  324381   2.959 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.474           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.381           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.096           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.904           ms/op
ClientGrpc.existUser                      sample  341926   2.807 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.379           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.802           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.305           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.259           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.557           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.004           ms/op
ClientGrpc.getUser                        sample  324164   2.958 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.702           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.949           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.174           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.668           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.158           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.170           ms/op
ClientGrpc.listUser                       sample  249652   3.843 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.090           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.874           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.434           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.185           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.807           ms/op
