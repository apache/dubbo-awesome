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
# Warmup Iteration   1: 4.400 ops/ms
# Warmup Iteration   2: 9.227 ops/ms
# Warmup Iteration   3: 10.707 ops/ms
Iteration   1: 10.951 ops/ms
Iteration   2: 10.870 ops/ms
Iteration   3: 10.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.937 ±(99.9%) 1.122 ops/ms [Average]
  (min, avg, max) = (10.870, 10.937, 10.991), stdev = 0.062
  CI (99.9%): [9.815, 12.059] (assumes normal distribution)


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
# Warmup Iteration   1: 8.005 ops/ms
# Warmup Iteration   2: 11.101 ops/ms
# Warmup Iteration   3: 11.525 ops/ms
Iteration   1: 11.157 ops/ms
Iteration   2: 11.531 ops/ms
Iteration   3: 11.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.311 ±(99.9%) 3.568 ops/ms [Average]
  (min, avg, max) = (11.157, 11.311, 11.531), stdev = 0.196
  CI (99.9%): [7.743, 14.879] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.058 ops/ms
# Warmup Iteration   2: 10.437 ops/ms
# Warmup Iteration   3: 10.642 ops/ms
Iteration   1: 10.839 ops/ms
Iteration   2: 10.864 ops/ms
Iteration   3: 10.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.827 ±(99.9%) 0.800 ops/ms [Average]
  (min, avg, max) = (10.779, 10.827, 10.864), stdev = 0.044
  CI (99.9%): [10.027, 11.627] (assumes normal distribution)


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
# Warmup Iteration   1: 5.880 ops/ms
# Warmup Iteration   2: 7.917 ops/ms
# Warmup Iteration   3: 8.325 ops/ms
Iteration   1: 8.300 ops/ms
Iteration   2: 8.240 ops/ms
Iteration   3: 8.103 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.214 ±(99.9%) 1.837 ops/ms [Average]
  (min, avg, max) = (8.103, 8.214, 8.300), stdev = 0.101
  CI (99.9%): [6.378, 10.051] (assumes normal distribution)


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
# Warmup Iteration   1: 3.915 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.011 ±(99.9%) 0.002 ms/op
Iteration   1: 2.996 ±(99.9%) 0.002 ms/op
Iteration   2: 2.967 ±(99.9%) 0.003 ms/op
Iteration   3: 2.966 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.976 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (2.966, 2.976, 2.996), stdev = 0.017
  CI (99.9%): [2.663, 3.290] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.648 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.846 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.837 ±(99.9%) 0.002 ms/op
Iteration   1: 2.852 ±(99.9%) 0.003 ms/op
Iteration   2: 2.863 ±(99.9%) 0.003 ms/op
Iteration   3: 2.890 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.868 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (2.852, 2.868, 2.890), stdev = 0.019
  CI (99.9%): [2.514, 3.223] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.940 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.003 ms/op
Iteration   1: 2.961 ±(99.9%) 0.003 ms/op
Iteration   2: 2.937 ±(99.9%) 0.002 ms/op
Iteration   3: 2.965 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.954 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (2.937, 2.954, 2.965), stdev = 0.015
  CI (99.9%): [2.682, 3.226] (assumes normal distribution)


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 4.122 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.018 ms/op
Iteration   1: 3.861 ±(99.9%) 0.023 ms/op
Iteration   2: 3.859 ±(99.9%) 0.013 ms/op
Iteration   3: 3.831 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.850 ±(99.9%) 0.299 ms/op [Average]
  (min, avg, max) = (3.831, 3.850, 3.861), stdev = 0.016
  CI (99.9%): [3.551, 4.149] (assumes normal distribution)


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
# Warmup Iteration   1: 4.060 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.006 ms/op
Iteration   1: 2.981 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.579 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  9.886 ms/op
                 createUser·p0.9999: 12.292 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   2: 2.984 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  10.279 ms/op
                 createUser·p0.9999: 18.981 ms/op
                 createUser·p1.00:   19.300 ms/op

Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.850 ms/op
                 createUser·p0.999:  10.444 ms/op
                 createUser·p0.9999: 26.750 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321158
  mean =      2.990 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31339 
    [ 2.500,  5.000) = 287559 
    [ 5.000,  7.500) = 1771 
    [ 7.500, 10.000) = 146 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.579 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =     10.235 ms/op
     p(99.9900) =     25.181 ms/op
     p(99.9990) =     28.436 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 3.599 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.970 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.887 ±(99.9%) 0.006 ms/op
Iteration   1: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.646 ms/op
                 existUser·p0.999:  8.389 ms/op
                 existUser·p0.9999: 13.011 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   2: 2.879 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.678 ms/op
                 existUser·p0.999:  7.314 ms/op
                 existUser·p0.9999: 14.775 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 2.873 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.682 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  6.711 ms/op
                 existUser·p0.9999: 15.808 ms/op
                 existUser·p1.00:   16.253 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332129
  mean =      2.891 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2691 
    [ 1.250,  2.500) = 45519 
    [ 2.500,  3.750) = 270744 
    [ 3.750,  5.000) = 11366 
    [ 5.000,  6.250) = 1113 
    [ 6.250,  7.500) = 288 
    [ 7.500,  8.750) = 194 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 54 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =      7.938 ms/op
     p(99.9900) =     15.119 ms/op
     p(99.9990) =     16.041 ms/op
     p(99.9999) =     16.253 ms/op
    p(100.0000) =     16.253 ms/op


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.572 ms/op
                 getUser·p0.9999: 11.928 ms/op
                 getUser·p1.00:   12.222 ms/op

Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.536 ms/op
                 getUser·p0.9999: 20.784 ms/op
                 getUser·p1.00:   21.660 ms/op

Iteration   3: 2.958 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.787 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.600 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  9.714 ms/op
                 getUser·p0.9999: 14.588 ms/op
                 getUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 322299
  mean =      2.978 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31103 
    [ 2.500,  5.000) = 289754 
    [ 5.000,  7.500) = 1010 
    [ 7.500, 10.000) = 202 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.482 ms/op
     p(99.9900) =     19.524 ms/op
     p(99.9990) =     21.539 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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
# Warmup Iteration   1: 5.041 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.010 ms/op
Iteration   1: 3.816 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   6.423 ms/op
                 listUser·p0.999:  12.574 ms/op
                 listUser·p0.9999: 18.502 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 3.844 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.442 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.411 ms/op
                 listUser·p0.9999: 19.410 ms/op
                 listUser·p1.00:   23.953 ms/op

Iteration   3: 3.915 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  17.158 ms/op
                 listUser·p0.9999: 25.848 ms/op
                 listUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248688
  mean =      3.858 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3961 
    [ 2.500,  5.000) = 225915 
    [ 5.000,  7.500) = 17750 
    [ 7.500, 10.000) = 569 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      3.715 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.587 ms/op
     p(99.9900) =     25.305 ms/op
     p(99.9990) =     26.002 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.937 ± 1.122  ops/ms
ClientGrpc.existUser                       thrpt       3  11.311 ± 3.568  ops/ms
ClientGrpc.getUser                         thrpt       3  10.827 ± 0.800  ops/ms
ClientGrpc.listUser                        thrpt       3   8.214 ± 1.837  ops/ms
ClientGrpc.createUser                       avgt       3   2.976 ± 0.314   ms/op
ClientGrpc.existUser                        avgt       3   2.868 ± 0.355   ms/op
ClientGrpc.getUser                          avgt       3   2.954 ± 0.272   ms/op
ClientGrpc.listUser                         avgt       3   3.850 ± 0.299   ms/op
ClientGrpc.createUser                     sample  321158   2.990 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.579           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.970           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.514           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.719           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.235           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.181           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.508           ms/op
ClientGrpc.existUser                      sample  332129   2.891 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.682           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.588           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.938           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.119           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.253           ms/op
ClientGrpc.getUser                        sample  322299   2.978 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.510           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.961           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.502           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.715           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.482           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.524           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.660           ms/op
ClientGrpc.listUser                       sample  248688   3.858 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.014           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.715           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.399           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.587           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.305           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.051           ms/op
