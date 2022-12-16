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
# Warmup Iteration   1: 4.304 ops/ms
# Warmup Iteration   2: 9.639 ops/ms
# Warmup Iteration   3: 10.358 ops/ms
Iteration   1: 10.628 ops/ms
Iteration   2: 10.174 ops/ms
Iteration   3: 10.365 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.389 ±(99.9%) 4.164 ops/ms [Average]
  (min, avg, max) = (10.174, 10.389, 10.628), stdev = 0.228
  CI (99.9%): [6.225, 14.553] (assumes normal distribution)


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
# Warmup Iteration   1: 7.965 ops/ms
# Warmup Iteration   2: 10.587 ops/ms
# Warmup Iteration   3: 10.926 ops/ms
Iteration   1: 11.026 ops/ms
Iteration   2: 11.030 ops/ms
Iteration   3: 10.970 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.009 ±(99.9%) 0.612 ops/ms [Average]
  (min, avg, max) = (10.970, 11.009, 11.030), stdev = 0.034
  CI (99.9%): [10.397, 11.621] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.396 ops/ms
# Warmup Iteration   2: 10.215 ops/ms
# Warmup Iteration   3: 10.121 ops/ms
Iteration   1: 10.491 ops/ms
Iteration   2: 10.366 ops/ms
Iteration   3: 10.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.515 ±(99.9%) 2.970 ops/ms [Average]
  (min, avg, max) = (10.366, 10.515, 10.689), stdev = 0.163
  CI (99.9%): [7.545, 13.485] (assumes normal distribution)


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
# Warmup Iteration   1: 7.363 ops/ms
# Warmup Iteration   2: 9.068 ops/ms
# Warmup Iteration   3: 7.888 ops/ms
Iteration   1: 8.049 ops/ms
Iteration   2: 7.974 ops/ms
Iteration   3: 7.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.002 ±(99.9%) 0.743 ops/ms [Average]
  (min, avg, max) = (7.974, 8.002, 8.049), stdev = 0.041
  CI (99.9%): [7.259, 8.745] (assumes normal distribution)


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
# Warmup Iteration   1: 3.658 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.993 ±(99.9%) 0.003 ms/op
Iteration   1: 2.933 ±(99.9%) 0.003 ms/op
Iteration   2: 2.975 ±(99.9%) 0.003 ms/op
Iteration   3: 3.107 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.005 ±(99.9%) 1.653 ms/op [Average]
  (min, avg, max) = (2.933, 3.005, 3.107), stdev = 0.091
  CI (99.9%): [1.351, 4.658] (assumes normal distribution)


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.966 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.002 ms/op
Iteration   1: 2.799 ±(99.9%) 0.003 ms/op
Iteration   2: 2.865 ±(99.9%) 0.003 ms/op
Iteration   3: 2.974 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.879 ±(99.9%) 1.610 ms/op [Average]
  (min, avg, max) = (2.799, 2.879, 2.974), stdev = 0.088
  CI (99.9%): [1.270, 4.489] (assumes normal distribution)


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.003 ms/op
Iteration   1: 2.974 ±(99.9%) 0.003 ms/op
Iteration   2: 3.076 ±(99.9%) 0.002 ms/op
Iteration   3: 3.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.054 ±(99.9%) 1.307 ms/op [Average]
  (min, avg, max) = (2.974, 3.054, 3.112), stdev = 0.072
  CI (99.9%): [1.747, 4.362] (assumes normal distribution)


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
# Warmup Iteration   1: 5.189 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.977 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 3.945 ±(99.9%) 0.012 ms/op
Iteration   1: 3.832 ±(99.9%) 0.003 ms/op
Iteration   2: 3.994 ±(99.9%) 0.031 ms/op
Iteration   3: 3.956 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.928 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (3.832, 3.928, 3.994), stdev = 0.085
  CI (99.9%): [2.381, 5.474] (assumes normal distribution)


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
Iteration   1: 3.081 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.174 ms/op
                 createUser·p0.999:  7.509 ms/op
                 createUser·p0.9999: 12.994 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   2: 3.040 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.692 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.129 ms/op
                 createUser·p0.999:  10.384 ms/op
                 createUser·p0.9999: 12.370 ms/op
                 createUser·p1.00:   16.695 ms/op

Iteration   3: 3.083 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.547 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  10.058 ms/op
                 createUser·p0.9999: 25.887 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312728
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25310 
    [ 2.500,  5.000) = 286272 
    [ 5.000,  7.500) = 712 
    [ 7.500, 10.000) = 115 
    [10.000, 12.500) = 198 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.547 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =     10.163 ms/op
     p(99.9900) =     22.535 ms/op
     p(99.9990) =     26.276 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 3.911 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.883 ±(99.9%) 0.006 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.535 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.740 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  8.347 ms/op
                 existUser·p0.9999: 11.441 ms/op
                 existUser·p1.00:   12.075 ms/op

Iteration   2: 2.997 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  7.936 ms/op
                 existUser·p0.9999: 13.156 ms/op
                 existUser·p1.00:   13.500 ms/op

Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.629 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  10.500 ms/op
                 existUser·p0.9999: 16.702 ms/op
                 existUser·p1.00:   17.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323390
  mean =      2.969 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3165 
    [ 1.250,  2.500) = 45954 
    [ 2.500,  3.750) = 255144 
    [ 3.750,  5.000) = 17858 
    [ 5.000,  6.250) = 586 
    [ 6.250,  7.500) = 292 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 75 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.733 ms/op
     p(99.9900) =     15.396 ms/op
     p(99.9990) =     16.984 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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
# Warmup Iteration   1: 3.864 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.007 ms/op
Iteration   1: 3.085 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.771 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  5.640 ms/op
                 getUser·p0.9999: 11.555 ms/op
                 getUser·p1.00:   11.780 ms/op

Iteration   2: 3.047 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.247 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  7.289 ms/op
                 getUser·p0.9999: 13.656 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 3.029 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.850 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.676 ms/op
                 getUser·p0.9999: 16.586 ms/op
                 getUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314444
  mean =      3.053 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1342 
    [ 1.250,  2.500) = 28529 
    [ 2.500,  3.750) = 258006 
    [ 3.750,  5.000) = 25823 
    [ 5.000,  6.250) = 273 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 42 
    [12.500, 13.750) = 52 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.247 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.222 ms/op
     p(99.9900) =     14.469 ms/op
     p(99.9990) =     16.964 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


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
# Warmup Iteration   1: 4.743 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.997 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.993 ±(99.9%) 0.011 ms/op
Iteration   1: 3.960 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  11.743 ms/op
                 listUser·p0.9999: 20.379 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   2: 3.951 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 19.297 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 3.940 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  15.921 ms/op
                 listUser·p0.9999: 22.669 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242916
  mean =      3.950 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4214 
    [ 2.500,  5.000) = 212692 
    [ 5.000,  7.500) = 24993 
    [ 7.500, 10.000) = 546 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.820 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     15.157 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.895 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.389 ± 4.164  ops/ms
ClientGrpc.existUser                       thrpt       3  11.009 ± 0.612  ops/ms
ClientGrpc.getUser                         thrpt       3  10.515 ± 2.970  ops/ms
ClientGrpc.listUser                        thrpt       3   8.002 ± 0.743  ops/ms
ClientGrpc.createUser                       avgt       3   3.005 ± 1.653   ms/op
ClientGrpc.existUser                        avgt       3   2.879 ± 1.610   ms/op
ClientGrpc.getUser                          avgt       3   3.054 ± 1.307   ms/op
ClientGrpc.listUser                         avgt       3   3.928 ± 1.546   ms/op
ClientGrpc.createUser                     sample  312728   3.068 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.547           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.797           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.163           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.535           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.345           ms/op
ClientGrpc.existUser                      sample  323390   2.969 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.535           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.793           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.733           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.396           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.138           ms/op
ClientGrpc.getUser                        sample  314444   3.053 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.247           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.222           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.469           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.105           ms/op
ClientGrpc.listUser                       sample  242916   3.950 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.820           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.157           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.151           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.970           ms/op
