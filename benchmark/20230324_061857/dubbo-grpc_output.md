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
# Warmup Iteration   1: 2.559 ops/ms
# Warmup Iteration   2: 6.414 ops/ms
# Warmup Iteration   3: 7.937 ops/ms
Iteration   1: 8.149 ops/ms
Iteration   2: 8.173 ops/ms
Iteration   3: 8.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.237 ±(99.9%) 2.406 ops/ms [Average]
  (min, avg, max) = (8.149, 8.237, 8.389), stdev = 0.132
  CI (99.9%): [5.830, 10.643] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.445 ops/ms
# Warmup Iteration   2: 8.539 ops/ms
# Warmup Iteration   3: 8.974 ops/ms
Iteration   1: 8.692 ops/ms
Iteration   2: 8.363 ops/ms
Iteration   3: 8.499 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.518 ±(99.9%) 3.017 ops/ms [Average]
  (min, avg, max) = (8.363, 8.518, 8.692), stdev = 0.165
  CI (99.9%): [5.501, 11.535] (assumes normal distribution)


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
# Warmup Iteration   1: 4.594 ops/ms
# Warmup Iteration   2: 7.514 ops/ms
# Warmup Iteration   3: 8.041 ops/ms
Iteration   1: 7.630 ops/ms
Iteration   2: 8.081 ops/ms
Iteration   3: 8.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.904 ±(99.9%) 4.394 ops/ms [Average]
  (min, avg, max) = (7.630, 7.904, 8.081), stdev = 0.241
  CI (99.9%): [3.510, 12.299] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.321 ops/ms
# Warmup Iteration   2: 6.026 ops/ms
# Warmup Iteration   3: 6.333 ops/ms
Iteration   1: 6.366 ops/ms
Iteration   2: 6.385 ops/ms
Iteration   3: 6.512 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.421 ±(99.9%) 1.450 ops/ms [Average]
  (min, avg, max) = (6.366, 6.421, 6.512), stdev = 0.079
  CI (99.9%): [4.971, 7.870] (assumes normal distribution)


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
# Warmup Iteration   1: 5.654 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.165 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.173 ±(99.9%) 0.019 ms/op
Iteration   1: 4.019 ±(99.9%) 0.002 ms/op
Iteration   2: 4.001 ±(99.9%) 0.003 ms/op
Iteration   3: 3.824 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.948 ±(99.9%) 1.971 ms/op [Average]
  (min, avg, max) = (3.824, 3.948, 4.019), stdev = 0.108
  CI (99.9%): [1.977, 5.919] (assumes normal distribution)


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
# Warmup Iteration   1: 5.334 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.847 ±(99.9%) 0.005 ms/op
Iteration   1: 3.693 ±(99.9%) 0.003 ms/op
Iteration   2: 3.590 ±(99.9%) 0.003 ms/op
Iteration   3: 3.512 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.598 ±(99.9%) 1.660 ms/op [Average]
  (min, avg, max) = (3.512, 3.598, 3.693), stdev = 0.091
  CI (99.9%): [1.939, 5.258] (assumes normal distribution)


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
# Warmup Iteration   1: 5.536 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.190 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.962 ±(99.9%) 0.015 ms/op
Iteration   1: 3.954 ±(99.9%) 0.005 ms/op
Iteration   2: 3.811 ±(99.9%) 0.004 ms/op
Iteration   3: 3.788 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.851 ±(99.9%) 1.638 ms/op [Average]
  (min, avg, max) = (3.788, 3.851, 3.954), stdev = 0.090
  CI (99.9%): [2.213, 5.489] (assumes normal distribution)


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
# Warmup Iteration   1: 7.546 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.261 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.195 ±(99.9%) 0.029 ms/op
Iteration   1: 5.200 ±(99.9%) 0.016 ms/op
Iteration   2: 5.096 ±(99.9%) 0.017 ms/op
Iteration   3: 4.909 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.068 ±(99.9%) 2.696 ms/op [Average]
  (min, avg, max) = (4.909, 5.068, 5.200), stdev = 0.148
  CI (99.9%): [2.372, 7.764] (assumes normal distribution)


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
# Warmup Iteration   1: 5.693 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.101 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.013 ms/op
Iteration   1: 3.818 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.817 ms/op
                 createUser·p0.95:   5.267 ms/op
                 createUser·p0.99:   6.726 ms/op
                 createUser·p0.999:  11.482 ms/op
                 createUser·p0.9999: 23.556 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 3.919 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.800 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   7.217 ms/op
                 createUser·p0.999:  12.088 ms/op
                 createUser·p0.9999: 21.130 ms/op
                 createUser·p1.00:   21.496 ms/op

Iteration   3: 3.970 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.973 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   6.947 ms/op
                 createUser·p0.999:  12.810 ms/op
                 createUser·p0.9999: 24.377 ms/op
                 createUser·p1.00:   25.264 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 246042
  mean =      3.901 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4620 
    [ 2.500,  5.000) = 220515 
    [ 5.000,  7.500) = 19216 
    [ 7.500, 10.000) = 1286 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.366 ms/op
     p(99.0000) =      6.968 ms/op
     p(99.9000) =     11.975 ms/op
     p(99.9900) =     23.658 ms/op
     p(99.9990) =     25.025 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


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
# Warmup Iteration   1: 5.496 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.011 ms/op
Iteration   1: 3.781 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  10.509 ms/op
                 existUser·p0.9999: 17.647 ms/op
                 existUser·p1.00:   20.316 ms/op

Iteration   2: 3.707 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  11.862 ms/op
                 existUser·p0.9999: 22.458 ms/op
                 existUser·p1.00:   22.839 ms/op

Iteration   3: 3.836 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.858 ms/op
                 existUser·p0.95:   5.407 ms/op
                 existUser·p0.99:   8.094 ms/op
                 existUser·p0.999:  13.304 ms/op
                 existUser·p0.9999: 36.379 ms/op
                 existUser·p1.00:   39.518 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 254354
  mean =      3.774 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7567 
    [ 2.500,  5.000) = 229451 
    [ 5.000,  7.500) = 15361 
    [ 7.500, 10.000) = 1409 
    [10.000, 12.500) = 357 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.794 ms/op
     p(50.0000) =      3.641 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.226 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     11.846 ms/op
     p(99.9900) =     35.164 ms/op
     p(99.9990) =     38.804 ms/op
     p(99.9999) =     39.518 ms/op
    p(100.0000) =     39.518 ms/op


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
# Warmup Iteration   1: 5.744 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.197 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.849 ±(99.9%) 0.011 ms/op
Iteration   1: 3.884 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.333 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  10.967 ms/op
                 getUser·p0.9999: 15.570 ms/op
                 getUser·p1.00:   16.220 ms/op

Iteration   2: 3.900 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.358 ms/op
                 getUser·p0.99:   6.946 ms/op
                 getUser·p0.999:  11.862 ms/op
                 getUser·p0.9999: 20.414 ms/op
                 getUser·p1.00:   20.775 ms/op

Iteration   3: 4.062 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.693 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  11.960 ms/op
                 getUser·p0.9999: 20.914 ms/op
                 getUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 243136
  mean =      3.947 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5860 
    [ 2.500,  5.000) = 213220 
    [ 5.000,  7.500) = 22286 
    [ 7.500, 10.000) = 1322 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     11.794 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     21.313 ms/op
     p(99.9999) =     21.496 ms/op
    p(100.0000) =     21.496 ms/op


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
# Warmup Iteration   1: 6.638 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 5.243 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.956 ±(99.9%) 0.018 ms/op
Iteration   1: 4.916 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.380 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.627 ms/op
                 listUser·p0.95:   7.414 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  16.758 ms/op
                 listUser·p0.9999: 21.757 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   2: 5.098 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.700 ms/op
                 listUser·p0.50:   4.792 ms/op
                 listUser·p0.90:   6.791 ms/op
                 listUser·p0.95:   7.733 ms/op
                 listUser·p0.99:   10.371 ms/op
                 listUser·p0.999:  18.363 ms/op
                 listUser·p0.9999: 24.869 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   3: 5.056 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.906 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   10.289 ms/op
                 listUser·p0.999:  18.928 ms/op
                 listUser·p0.9999: 30.463 ms/op
                 listUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 191116
  mean =      5.022 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 671 
    [ 2.500,  5.000) = 114943 
    [ 5.000,  7.500) = 64934 
    [ 7.500, 10.000) = 8552 
    [10.000, 12.500) = 1373 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      4.719 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.635 ms/op
     p(99.0000) =     10.109 ms/op
     p(99.9000) =     18.048 ms/op
     p(99.9900) =     27.652 ms/op
     p(99.9990) =     30.900 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.237 ± 2.406  ops/ms
ClientGrpc.existUser                       thrpt       3   8.518 ± 3.017  ops/ms
ClientGrpc.getUser                         thrpt       3   7.904 ± 4.394  ops/ms
ClientGrpc.listUser                        thrpt       3   6.421 ± 1.450  ops/ms
ClientGrpc.createUser                       avgt       3   3.948 ± 1.971   ms/op
ClientGrpc.existUser                        avgt       3   3.598 ± 1.660   ms/op
ClientGrpc.getUser                          avgt       3   3.851 ± 1.638   ms/op
ClientGrpc.listUser                         avgt       3   5.068 ± 2.696   ms/op
ClientGrpc.createUser                     sample  246042   3.901 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.800           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.968           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.975           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.658           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.264           ms/op
ClientGrpc.existUser                      sample  254354   3.774 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.794           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.641           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.743           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.226           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.037           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.846           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          35.164           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          39.518           ms/op
ClientGrpc.getUser                        sample  243136   3.947 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.948           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.997           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.480           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.102           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.794           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.382           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.496           ms/op
ClientGrpc.listUser                       sample  191116   5.022 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.700           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.775           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.635           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.109           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.048           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.652           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.900           ms/op
