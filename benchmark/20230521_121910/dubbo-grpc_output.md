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
# Warmup Iteration   1: 4.218 ops/ms
# Warmup Iteration   2: 9.161 ops/ms
# Warmup Iteration   3: 10.069 ops/ms
Iteration   1: 10.549 ops/ms
Iteration   2: 10.592 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.587 ±(99.9%) 0.656 ops/ms [Average]
  (min, avg, max) = (10.549, 10.587, 10.620), stdev = 0.036
  CI (99.9%): [9.931, 11.243] (assumes normal distribution)


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
# Warmup Iteration   1: 7.615 ops/ms
# Warmup Iteration   2: 10.780 ops/ms
# Warmup Iteration   3: 10.890 ops/ms
Iteration   1: 11.118 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.884 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.877 ±(99.9%) 4.482 ops/ms [Average]
  (min, avg, max) = (10.627, 10.877, 11.118), stdev = 0.246
  CI (99.9%): [6.395, 15.358] (assumes normal distribution)


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
# Warmup Iteration   1: 6.799 ops/ms
# Warmup Iteration   2: 10.259 ops/ms
# Warmup Iteration   3: 10.308 ops/ms
Iteration   1: 10.632 ops/ms
Iteration   2: 10.704 ops/ms
Iteration   3: 10.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.632 ±(99.9%) 1.321 ops/ms [Average]
  (min, avg, max) = (10.560, 10.632, 10.704), stdev = 0.072
  CI (99.9%): [9.311, 11.953] (assumes normal distribution)


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
# Warmup Iteration   1: 6.299 ops/ms
# Warmup Iteration   2: 7.934 ops/ms
# Warmup Iteration   3: 8.244 ops/ms
Iteration   1: 8.431 ops/ms
Iteration   2: 8.336 ops/ms
Iteration   3: 8.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.317 ±(99.9%) 2.268 ops/ms [Average]
  (min, avg, max) = (8.185, 8.317, 8.431), stdev = 0.124
  CI (99.9%): [6.049, 10.586] (assumes normal distribution)


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
# Warmup Iteration   1: 4.072 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.070 ±(99.9%) 0.004 ms/op
Iteration   1: 3.050 ±(99.9%) 0.003 ms/op
Iteration   2: 3.076 ±(99.9%) 0.003 ms/op
Iteration   3: 3.009 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.045 ±(99.9%) 0.619 ms/op [Average]
  (min, avg, max) = (3.009, 3.045, 3.076), stdev = 0.034
  CI (99.9%): [2.426, 3.665] (assumes normal distribution)


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
# Warmup Iteration   1: 3.916 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.927 ±(99.9%) 0.004 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 2.916 ±(99.9%) 0.003 ms/op
Iteration   3: 2.900 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (2.900, 2.908, 2.916), stdev = 0.008
  CI (99.9%): [2.763, 3.053] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.003 ms/op
Iteration   1: 2.978 ±(99.9%) 0.004 ms/op
Iteration   2: 3.027 ±(99.9%) 0.003 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.004 ±(99.9%) 0.450 ms/op [Average]
  (min, avg, max) = (2.978, 3.004, 3.027), stdev = 0.025
  CI (99.9%): [2.554, 3.454] (assumes normal distribution)


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
# Warmup Iteration   1: 5.099 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.045 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.030 ms/op
Iteration   1: 3.925 ±(99.9%) 0.016 ms/op
Iteration   2: 3.849 ±(99.9%) 0.011 ms/op
Iteration   3: 3.900 ±(99.9%) 0.038 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.891 ±(99.9%) 0.713 ms/op [Average]
  (min, avg, max) = (3.849, 3.891, 3.925), stdev = 0.039
  CI (99.9%): [3.178, 4.605] (assumes normal distribution)


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
# Warmup Iteration   1: 4.244 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.736 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.348 ms/op
                 createUser·p0.9999: 11.395 ms/op
                 createUser·p1.00:   13.533 ms/op

Iteration   2: 3.091 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  6.740 ms/op
                 createUser·p0.9999: 12.806 ms/op
                 createUser·p1.00:   13.402 ms/op

Iteration   3: 3.099 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.240 ms/op
                 createUser·p0.9999: 16.864 ms/op
                 createUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311996
  mean =      3.080 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 873 
    [ 1.250,  2.500) = 19642 
    [ 2.500,  3.750) = 269012 
    [ 3.750,  5.000) = 21055 
    [ 5.000,  6.250) = 848 
    [ 6.250,  7.500) = 238 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 91 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.733 ms/op
     p(99.9900) =     15.395 ms/op
     p(99.9990) =     17.199 ms/op
     p(99.9999) =     17.269 ms/op
    p(100.0000) =     17.269 ms/op


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
# Warmup Iteration   1: 3.886 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
Iteration   1: 2.933 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.664 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  6.275 ms/op
                 existUser·p0.9999: 19.140 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 2.936 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.678 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 13.043 ms/op
                 existUser·p1.00:   13.320 ms/op

Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.240 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.177 ms/op
                 existUser·p0.9999: 17.934 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326440
  mean =      2.939 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1749 
    [ 1.250,  2.500) = 30690 
    [ 2.500,  3.750) = 280626 
    [ 3.750,  5.000) = 11891 
    [ 5.000,  6.250) = 1005 
    [ 6.250,  7.500) = 152 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 53 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.240 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.628 ms/op
     p(99.9900) =     18.439 ms/op
     p(99.9990) =     19.357 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 4.144 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.077 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.733 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.971 ms/op
                 getUser·p0.9999: 11.954 ms/op
                 getUser·p1.00:   12.206 ms/op

Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  7.835 ms/op
                 getUser·p0.9999: 14.502 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 3.064 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.036 ms/op
                 getUser·p0.9999: 23.251 ms/op
                 getUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312676
  mean =      3.068 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16786 
    [ 2.500,  5.000) = 294697 
    [ 5.000,  7.500) = 904 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.277 ms/op
     p(99.9900) =     20.963 ms/op
     p(99.9990) =     24.723 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 5.095 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.010 ms/op
Iteration   1: 3.945 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.249 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  11.591 ms/op
                 listUser·p0.9999: 16.905 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   2: 3.846 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.656 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  17.367 ms/op
                 listUser·p0.9999: 27.416 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   3: 3.959 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.505 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  13.502 ms/op
                 listUser·p0.9999: 17.269 ms/op
                 listUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245274
  mean =      3.916 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5384 
    [ 2.500,  5.000) = 216935 
    [ 5.000,  7.500) = 21787 
    [ 7.500, 10.000) = 741 
    [10.000, 12.500) = 112 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.505 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.086 ms/op
     p(99.9900) =     23.429 ms/op
     p(99.9990) =     27.695 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.587 ± 0.656  ops/ms
ClientGrpc.existUser                       thrpt       3  10.877 ± 4.482  ops/ms
ClientGrpc.getUser                         thrpt       3  10.632 ± 1.321  ops/ms
ClientGrpc.listUser                        thrpt       3   8.317 ± 2.268  ops/ms
ClientGrpc.createUser                       avgt       3   3.045 ± 0.619   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 0.145   ms/op
ClientGrpc.getUser                          avgt       3   3.004 ± 0.450   ms/op
ClientGrpc.listUser                         avgt       3   3.891 ± 0.713   ms/op
ClientGrpc.createUser                     sample  311996   3.080 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.598           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.733           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.395           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.269           ms/op
ClientGrpc.existUser                      sample  326440   2.939 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.240           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.514           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.628           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.439           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.399           ms/op
ClientGrpc.getUser                        sample  312676   3.068 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.593           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.277           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.963           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.805           ms/op
ClientGrpc.listUser                       sample  245274   3.916 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.505           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.940           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.086           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.429           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.787           ms/op
