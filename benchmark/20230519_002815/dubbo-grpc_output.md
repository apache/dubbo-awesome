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
# Warmup Iteration   1: 4.275 ops/ms
# Warmup Iteration   2: 8.246 ops/ms
# Warmup Iteration   3: 9.809 ops/ms
Iteration   1: 10.215 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 10.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.251 ±(99.9%) 0.795 ops/ms [Average]
  (min, avg, max) = (10.215, 10.251, 10.299), stdev = 0.044
  CI (99.9%): [9.455, 11.046] (assumes normal distribution)


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
# Warmup Iteration   1: 7.342 ops/ms
# Warmup Iteration   2: 10.470 ops/ms
# Warmup Iteration   3: 10.956 ops/ms
Iteration   1: 10.756 ops/ms
Iteration   2: 10.935 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.808 ±(99.9%) 2.019 ops/ms [Average]
  (min, avg, max) = (10.733, 10.808, 10.935), stdev = 0.111
  CI (99.9%): [8.789, 12.827] (assumes normal distribution)


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
# Warmup Iteration   1: 6.348 ops/ms
# Warmup Iteration   2: 9.874 ops/ms
# Warmup Iteration   3: 10.109 ops/ms
Iteration   1: 10.457 ops/ms
Iteration   2: 10.278 ops/ms
Iteration   3: 10.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.339 ±(99.9%) 1.864 ops/ms [Average]
  (min, avg, max) = (10.278, 10.339, 10.457), stdev = 0.102
  CI (99.9%): [8.475, 12.204] (assumes normal distribution)


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
# Warmup Iteration   1: 5.433 ops/ms
# Warmup Iteration   2: 7.515 ops/ms
# Warmup Iteration   3: 7.839 ops/ms
Iteration   1: 7.828 ops/ms
Iteration   2: 8.361 ops/ms
Iteration   3: 7.913 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.034 ±(99.9%) 5.226 ops/ms [Average]
  (min, avg, max) = (7.828, 8.034, 8.361), stdev = 0.286
  CI (99.9%): [2.808, 13.260] (assumes normal distribution)


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
# Warmup Iteration   1: 4.389 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.072 ±(99.9%) 0.003 ms/op
Iteration   2: 3.049 ±(99.9%) 0.002 ms/op
Iteration   3: 2.950 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.024 ±(99.9%) 1.176 ms/op [Average]
  (min, avg, max) = (2.950, 3.024, 3.072), stdev = 0.064
  CI (99.9%): [1.847, 4.200] (assumes normal distribution)


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.879 ±(99.9%) 0.003 ms/op
Iteration   1: 2.976 ±(99.9%) 0.002 ms/op
Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
Iteration   3: 2.842 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.919 ±(99.9%) 1.267 ms/op [Average]
  (min, avg, max) = (2.842, 2.919, 2.976), stdev = 0.069
  CI (99.9%): [1.652, 4.186] (assumes normal distribution)


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
# Warmup Iteration   1: 4.693 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.232 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.003 ms/op
Iteration   1: 3.062 ±(99.9%) 0.002 ms/op
Iteration   2: 3.054 ±(99.9%) 0.002 ms/op
Iteration   3: 3.034 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.050 ±(99.9%) 0.264 ms/op [Average]
  (min, avg, max) = (3.034, 3.050, 3.062), stdev = 0.014
  CI (99.9%): [2.785, 3.314] (assumes normal distribution)


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
# Warmup Iteration   1: 5.692 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.138 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.009 ms/op
Iteration   1: 4.169 ±(99.9%) 0.012 ms/op
Iteration   2: 4.088 ±(99.9%) 0.011 ms/op
Iteration   3: 4.093 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.117 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (4.088, 4.117, 4.169), stdev = 0.045
  CI (99.9%): [3.293, 4.941] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.430 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.236 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
Iteration   1: 3.120 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  7.527 ms/op
                 createUser·p0.9999: 15.499 ms/op
                 createUser·p1.00:   15.745 ms/op

Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.337 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  10.881 ms/op
                 createUser·p0.9999: 18.278 ms/op
                 createUser·p1.00:   18.678 ms/op

Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.785 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  9.307 ms/op
                 createUser·p0.9999: 18.168 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314112
  mean =      3.056 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 509 
    [ 1.250,  2.500) = 18923 
    [ 2.500,  3.750) = 277063 
    [ 3.750,  5.000) = 15969 
    [ 5.000,  6.250) = 958 
    [ 6.250,  7.500) = 286 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 53 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 41 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 41 

  Percentiles, ms/op:
      p(0.0000) =      0.337 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =     10.617 ms/op
     p(99.9900) =     17.995 ms/op
     p(99.9990) =     18.865 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 4.152 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.877 ±(99.9%) 0.006 ms/op
Iteration   1: 2.870 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.338 ms/op
                 existUser·p0.99:   3.893 ms/op
                 existUser·p0.999:  5.277 ms/op
                 existUser·p0.9999: 27.021 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   2: 2.894 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  11.017 ms/op
                 existUser·p0.9999: 36.700 ms/op
                 existUser·p1.00:   37.028 ms/op

Iteration   3: 2.895 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  7.029 ms/op
                 existUser·p0.9999: 23.121 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332543
  mean =      2.886 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41020 
    [ 2.500,  5.000) = 290843 
    [ 5.000,  7.500) = 438 
    [ 7.500, 10.000) = 18 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.638 ms/op
     p(50.0000) =      2.863 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.457 ms/op
     p(99.0000) =      4.063 ms/op
     p(99.9000) =      7.037 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     37.007 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 4.424 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.767 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.932 ms/op
                 getUser·p0.999:  8.090 ms/op
                 getUser·p0.9999: 20.251 ms/op
                 getUser·p1.00:   20.578 ms/op

Iteration   2: 3.060 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.544 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.056 ms/op
                 getUser·p0.9999: 18.090 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.850 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  6.964 ms/op
                 getUser·p0.9999: 19.651 ms/op
                 getUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313048
  mean =      3.066 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16274 
    [ 2.500,  5.000) = 294586 
    [ 5.000,  7.500) = 1858 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.544 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      7.610 ms/op
     p(99.9900) =     19.837 ms/op
     p(99.9990) =     20.471 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 5.567 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.325 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.011 ms/op
Iteration   1: 4.008 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  14.078 ms/op
                 listUser·p0.9999: 16.384 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   2: 4.054 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.877 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  14.862 ms/op
                 listUser·p0.9999: 17.083 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 4.101 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.741 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.923 ms/op
                 listUser·p0.99:   7.461 ms/op
                 listUser·p0.999:  15.761 ms/op
                 listUser·p0.9999: 20.558 ms/op
                 listUser·p1.00:   20.808 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 236691
  mean =      4.054 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3421 
    [ 2.500,  5.000) = 207136 
    [ 5.000,  7.500) = 24438 
    [ 7.500, 10.000) = 1141 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 192 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.741 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.890 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     14.739 ms/op
     p(99.9900) =     18.863 ms/op
     p(99.9990) =     20.751 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.251 ± 0.795  ops/ms
ClientGrpc.existUser                       thrpt       3  10.808 ± 2.019  ops/ms
ClientGrpc.getUser                         thrpt       3  10.339 ± 1.864  ops/ms
ClientGrpc.listUser                        thrpt       3   8.034 ± 5.226  ops/ms
ClientGrpc.createUser                       avgt       3   3.024 ± 1.176   ms/op
ClientGrpc.existUser                        avgt       3   2.919 ± 1.267   ms/op
ClientGrpc.getUser                          avgt       3   3.050 ± 0.264   ms/op
ClientGrpc.listUser                         avgt       3   4.117 ± 0.824   ms/op
ClientGrpc.createUser                     sample  314112   3.056 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.337           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.023           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.551           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.617           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.995           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.038           ms/op
ClientGrpc.existUser                      sample  332543   2.886 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.638           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.863           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.289           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.063           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.037           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.263           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          37.028           ms/op
ClientGrpc.getUser                        sample  313048   3.066 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.544           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.027           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.559           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.610           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.837           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.578           ms/op
ClientGrpc.listUser                       sample  236691   4.054 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.741           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.887           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.160           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.739           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.863           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.808           ms/op
