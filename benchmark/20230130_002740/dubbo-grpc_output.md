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
# Warmup Iteration   1: 3.350 ops/ms
# Warmup Iteration   2: 7.309 ops/ms
# Warmup Iteration   3: 8.330 ops/ms
Iteration   1: 8.725 ops/ms
Iteration   2: 8.923 ops/ms
Iteration   3: 8.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.640 ±(99.9%) 6.103 ops/ms [Average]
  (min, avg, max) = (8.271, 8.640, 8.923), stdev = 0.335
  CI (99.9%): [2.536, 14.743] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.137 ops/ms
# Warmup Iteration   2: 8.552 ops/ms
# Warmup Iteration   3: 8.700 ops/ms
Iteration   1: 9.021 ops/ms
Iteration   2: 9.218 ops/ms
Iteration   3: 9.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.080 ±(99.9%) 2.188 ops/ms [Average]
  (min, avg, max) = (9.001, 9.080, 9.218), stdev = 0.120
  CI (99.9%): [6.893, 11.268] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.798 ops/ms
# Warmup Iteration   2: 8.369 ops/ms
# Warmup Iteration   3: 8.533 ops/ms
Iteration   1: 8.391 ops/ms
Iteration   2: 8.378 ops/ms
Iteration   3: 8.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.451 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (8.378, 8.451, 8.583), stdev = 0.115
  CI (99.9%): [6.358, 10.543] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.001 ops/ms
# Warmup Iteration   2: 6.464 ops/ms
# Warmup Iteration   3: 6.927 ops/ms
Iteration   1: 6.798 ops/ms
Iteration   2: 7.144 ops/ms
Iteration   3: 6.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.924 ±(99.9%) 3.489 ops/ms [Average]
  (min, avg, max) = (6.798, 6.924, 7.144), stdev = 0.191
  CI (99.9%): [3.435, 10.413] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.379 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.003 ms/op
Iteration   1: 3.886 ±(99.9%) 0.002 ms/op
Iteration   2: 3.803 ±(99.9%) 0.001 ms/op
Iteration   3: 3.757 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.815 ±(99.9%) 1.193 ms/op [Average]
  (min, avg, max) = (3.757, 3.815, 3.886), stdev = 0.065
  CI (99.9%): [2.622, 5.008] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.839 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.004 ms/op
Iteration   1: 3.524 ±(99.9%) 0.003 ms/op
Iteration   2: 3.554 ±(99.9%) 0.004 ms/op
Iteration   3: 3.429 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.502 ±(99.9%) 1.196 ms/op [Average]
  (min, avg, max) = (3.429, 3.502, 3.554), stdev = 0.066
  CI (99.9%): [2.306, 4.698] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.204 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.003 ms/op
Iteration   1: 3.718 ±(99.9%) 0.003 ms/op
Iteration   2: 3.642 ±(99.9%) 0.004 ms/op
Iteration   3: 3.775 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.712 ±(99.9%) 1.216 ms/op [Average]
  (min, avg, max) = (3.642, 3.712, 3.775), stdev = 0.067
  CI (99.9%): [2.496, 4.928] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.844 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.939 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.806 ±(99.9%) 0.030 ms/op
Iteration   1: 4.783 ±(99.9%) 0.014 ms/op
Iteration   2: 4.788 ±(99.9%) 0.008 ms/op
Iteration   3: 4.600 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.724 ±(99.9%) 1.958 ms/op [Average]
  (min, avg, max) = (4.600, 4.724, 4.788), stdev = 0.107
  CI (99.9%): [2.766, 6.682] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.540 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.009 ms/op
Iteration   1: 3.648 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  11.436 ms/op
                 createUser·p0.9999: 15.441 ms/op
                 createUser·p1.00:   15.909 ms/op

Iteration   2: 3.662 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.527 ms/op
                 createUser·p0.50:   3.637 ms/op
                 createUser·p0.90:   4.178 ms/op
                 createUser·p0.95:   4.497 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 23.790 ms/op
                 createUser·p1.00:   24.019 ms/op

Iteration   3: 3.567 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.937 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  12.286 ms/op
                 createUser·p0.9999: 19.760 ms/op
                 createUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264738
  mean =      3.625 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8302 
    [ 2.500,  5.000) = 252038 
    [ 5.000,  7.500) = 3896 
    [ 7.500, 10.000) = 193 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.527 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =     11.735 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     23.944 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.310 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.008 ms/op
Iteration   1: 3.554 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  7.282 ms/op
                 existUser·p0.9999: 16.105 ms/op
                 existUser·p1.00:   16.597 ms/op

Iteration   2: 3.503 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   3.494 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  7.307 ms/op
                 existUser·p0.9999: 23.949 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   3: 3.381 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  7.348 ms/op
                 existUser·p0.9999: 20.399 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276107
  mean =      3.478 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17526 
    [ 2.500,  5.000) = 255036 
    [ 5.000,  7.500) = 3305 
    [ 7.500, 10.000) = 106 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =      7.307 ms/op
     p(99.9900) =     23.442 ms/op
     p(99.9990) =     24.289 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.580 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.008 ms/op
Iteration   1: 3.664 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.881 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  8.718 ms/op
                 getUser·p0.9999: 14.677 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 3.669 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   3.645 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.694 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  8.036 ms/op
                 getUser·p0.9999: 14.701 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   3: 3.643 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.976 ms/op
                 getUser·p0.50:   3.613 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  10.777 ms/op
                 getUser·p0.9999: 20.513 ms/op
                 getUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262331
  mean =      3.659 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8875 
    [ 2.500,  5.000) = 247655 
    [ 5.000,  7.500) = 5227 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =      8.684 ms/op
     p(99.9900) =     18.790 ms/op
     p(99.9990) =     20.824 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 5.696 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.150 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.768 ±(99.9%) 0.014 ms/op
Iteration   1: 4.696 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.513 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  14.870 ms/op
                 listUser·p0.9999: 23.310 ms/op
                 listUser·p1.00:   23.888 ms/op

Iteration   2: 4.572 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.509 ms/op
                 listUser·p0.50:   4.424 ms/op
                 listUser·p0.90:   5.505 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  17.433 ms/op
                 listUser·p0.9999: 23.495 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   3: 4.694 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.488 ms/op
                 listUser·p0.99:   8.045 ms/op
                 listUser·p0.999:  19.788 ms/op
                 listUser·p0.9999: 29.012 ms/op
                 listUser·p1.00:   29.327 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206203
  mean =      4.653 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 513 
    [ 2.500,  5.000) = 164676 
    [ 5.000,  7.500) = 37642 
    [ 7.500, 10.000) = 2865 
    [10.000, 12.500) = 187 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.069 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.472 ms/op
     p(99.0000) =      7.922 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     23.900 ms/op
     p(99.9990) =     29.284 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.640 ± 6.103  ops/ms
ClientGrpc.existUser                       thrpt       3   9.080 ± 2.188  ops/ms
ClientGrpc.getUser                         thrpt       3   8.451 ± 2.093  ops/ms
ClientGrpc.listUser                        thrpt       3   6.924 ± 3.489  ops/ms
ClientGrpc.createUser                       avgt       3   3.815 ± 1.193   ms/op
ClientGrpc.existUser                        avgt       3   3.502 ± 1.196   ms/op
ClientGrpc.getUser                          avgt       3   3.712 ± 1.216   ms/op
ClientGrpc.listUser                         avgt       3   4.724 ± 1.958   ms/op
ClientGrpc.createUser                     sample  264738   3.625 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.527           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.633           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.157           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.735           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.298           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.019           ms/op
ClientGrpc.existUser                      sample  276107   3.478 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.598           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.128           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.307           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.442           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.445           ms/op
ClientGrpc.getUser                        sample  262331   3.659 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.881           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.407           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.684           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.790           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.972           ms/op
ClientGrpc.listUser                       sample  206203   4.653 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.069           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.472           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.088           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.900           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.327           ms/op
