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
# Warmup Iteration   1: 4.069 ops/ms
# Warmup Iteration   2: 8.995 ops/ms
# Warmup Iteration   3: 9.914 ops/ms
Iteration   1: 10.548 ops/ms
Iteration   2: 10.792 ops/ms
Iteration   3: 10.571 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.637 ±(99.9%) 2.467 ops/ms [Average]
  (min, avg, max) = (10.548, 10.637, 10.792), stdev = 0.135
  CI (99.9%): [8.169, 13.104] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.209 ops/ms
# Warmup Iteration   2: 10.597 ops/ms
# Warmup Iteration   3: 11.014 ops/ms
Iteration   1: 11.202 ops/ms
Iteration   2: 10.939 ops/ms
Iteration   3: 10.911 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.017 ±(99.9%) 2.934 ops/ms [Average]
  (min, avg, max) = (10.911, 11.017, 11.202), stdev = 0.161
  CI (99.9%): [8.083, 13.952] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 6.906 ops/ms
# Warmup Iteration   2: 10.156 ops/ms
# Warmup Iteration   3: 10.424 ops/ms
Iteration   1: 10.695 ops/ms
Iteration   2: 10.710 ops/ms
Iteration   3: 10.694 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.700 ±(99.9%) 0.162 ops/ms [Average]
  (min, avg, max) = (10.694, 10.700, 10.710), stdev = 0.009
  CI (99.9%): [10.538, 10.862] (assumes normal distribution)


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
# Warmup Iteration   1: 5.667 ops/ms
# Warmup Iteration   2: 7.693 ops/ms
# Warmup Iteration   3: 8.094 ops/ms
Iteration   1: 8.202 ops/ms
Iteration   2: 8.089 ops/ms
Iteration   3: 8.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.132 ±(99.9%) 1.109 ops/ms [Average]
  (min, avg, max) = (8.089, 8.132, 8.202), stdev = 0.061
  CI (99.9%): [7.023, 9.241] (assumes normal distribution)


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
# Warmup Iteration   1: 4.177 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.201 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.003 ms/op
Iteration   1: 3.029 ±(99.9%) 0.009 ms/op
Iteration   2: 3.025 ±(99.9%) 0.003 ms/op
Iteration   3: 3.005 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.020 ±(99.9%) 0.240 ms/op [Average]
  (min, avg, max) = (3.005, 3.020, 3.029), stdev = 0.013
  CI (99.9%): [2.780, 3.260] (assumes normal distribution)


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.908 ±(99.9%) 0.002 ms/op
Iteration   1: 2.900 ±(99.9%) 0.002 ms/op
Iteration   2: 2.928 ±(99.9%) 0.001 ms/op
Iteration   3: 2.927 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.918 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.900, 2.918, 2.928), stdev = 0.016
  CI (99.9%): [2.628, 3.209] (assumes normal distribution)


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
# Warmup Iteration   1: 4.455 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.140 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.003 ms/op
Iteration   1: 3.026 ±(99.9%) 0.003 ms/op
Iteration   2: 3.028 ±(99.9%) 0.004 ms/op
Iteration   3: 3.046 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.033 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.026, 3.033, 3.046), stdev = 0.011
  CI (99.9%): [2.834, 3.232] (assumes normal distribution)


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
# Warmup Iteration   1: 4.985 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.867 ±(99.9%) 0.008 ms/op
Iteration   1: 3.891 ±(99.9%) 0.016 ms/op
Iteration   2: 3.878 ±(99.9%) 0.008 ms/op
Iteration   3: 3.922 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.897 ±(99.9%) 0.409 ms/op [Average]
  (min, avg, max) = (3.878, 3.897, 3.922), stdev = 0.022
  CI (99.9%): [3.488, 4.305] (assumes normal distribution)


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.220 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.006 ms/op
Iteration   1: 2.978 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.948 ms/op
                 createUser·p0.9999: 15.516 ms/op
                 createUser·p1.00:   15.925 ms/op

Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.491 ms/op
                 createUser·p0.9999: 14.853 ms/op
                 createUser·p1.00:   15.811 ms/op

Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.694 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  11.010 ms/op
                 createUser·p0.9999: 16.663 ms/op
                 createUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318707
  mean =      3.011 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 972 
    [ 1.250,  2.500) = 24241 
    [ 2.500,  3.750) = 278155 
    [ 3.750,  5.000) = 14002 
    [ 5.000,  6.250) = 561 
    [ 6.250,  7.500) = 294 
    [ 7.500,  8.750) = 145 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 66 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      9.049 ms/op
     p(99.9900) =     16.321 ms/op
     p(99.9990) =     16.863 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.964 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.903 ±(99.9%) 0.005 ms/op
Iteration   1: 2.872 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.708 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   3.932 ms/op
                 existUser·p0.999:  6.434 ms/op
                 existUser·p0.9999: 19.694 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   2: 2.895 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.278 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.371 ms/op
                 existUser·p0.9999: 13.827 ms/op
                 existUser·p1.00:   14.041 ms/op

Iteration   3: 2.812 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.585 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.297 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.026 ms/op
                 existUser·p0.999:  6.359 ms/op
                 existUser·p0.9999: 27.066 ms/op
                 existUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335666
  mean =      2.860 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46205 
    [ 2.500,  5.000) = 288437 
    [ 5.000,  7.500) = 757 
    [ 7.500, 10.000) = 76 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.278 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.310 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      6.737 ms/op
     p(99.9900) =     20.134 ms/op
     p(99.9990) =     27.350 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.008 ms/op
Iteration   1: 3.059 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  8.135 ms/op
                 getUser·p0.9999: 13.638 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.750 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  7.266 ms/op
                 getUser·p0.9999: 14.025 ms/op
                 getUser·p1.00:   14.254 ms/op

Iteration   3: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.666 ms/op
                 getUser·p0.50:   2.984 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  6.509 ms/op
                 getUser·p0.9999: 15.860 ms/op
                 getUser·p1.00:   16.351 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317241
  mean =      3.026 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 666 
    [ 1.250,  2.500) = 24389 
    [ 2.500,  3.750) = 275269 
    [ 3.750,  5.000) = 15328 
    [ 5.000,  6.250) = 1020 
    [ 6.250,  7.500) = 284 
    [ 7.500,  8.750) = 67 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 38 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.650 ms/op
     p(99.9000) =      7.100 ms/op
     p(99.9900) =     15.197 ms/op
     p(99.9990) =     16.165 ms/op
     p(99.9999) =     16.351 ms/op
    p(100.0000) =     16.351 ms/op


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.010 ms/op
Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  13.270 ms/op
                 listUser·p0.9999: 22.964 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 3.867 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  14.914 ms/op
                 listUser·p0.9999: 20.462 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 3.830 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  16.761 ms/op
                 listUser·p0.9999: 22.344 ms/op
                 listUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247256
  mean =      3.883 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3754 
    [ 2.500,  5.000) = 224619 
    [ 5.000,  7.500) = 17666 
    [ 7.500, 10.000) = 688 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.727 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.849 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     22.366 ms/op
     p(99.9990) =     23.205 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.637 ± 2.467  ops/ms
ClientGrpc.existUser                       thrpt       3  11.017 ± 2.934  ops/ms
ClientGrpc.getUser                         thrpt       3  10.700 ± 0.162  ops/ms
ClientGrpc.listUser                        thrpt       3   8.132 ± 1.109  ops/ms
ClientGrpc.createUser                       avgt       3   3.020 ± 0.240   ms/op
ClientGrpc.existUser                        avgt       3   2.918 ± 0.291   ms/op
ClientGrpc.getUser                          avgt       3   3.033 ± 0.199   ms/op
ClientGrpc.listUser                         avgt       3   3.897 ± 0.409   ms/op
ClientGrpc.createUser                     sample  318707   3.011 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.694           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.049           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.321           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.941           ms/op
ClientGrpc.existUser                      sample  335666   2.860 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.278           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.310           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.059           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.737           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.134           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          27.460           ms/op
ClientGrpc.getUser                        sample  317241   3.026 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.666           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.539           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.650           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.100           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.197           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.351           ms/op
ClientGrpc.listUser                       sample  247256   3.883 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.153           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.727           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.877           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.366           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.331           ms/op
