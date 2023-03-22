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
# Warmup Iteration   1: 3.231 ops/ms
# Warmup Iteration   2: 7.226 ops/ms
# Warmup Iteration   3: 8.431 ops/ms
Iteration   1: 8.886 ops/ms
Iteration   2: 8.881 ops/ms
Iteration   3: 8.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.847 ±(99.9%) 1.166 ops/ms [Average]
  (min, avg, max) = (8.773, 8.847, 8.886), stdev = 0.064
  CI (99.9%): [7.681, 10.013] (assumes normal distribution)


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
# Warmup Iteration   1: 5.946 ops/ms
# Warmup Iteration   2: 8.852 ops/ms
# Warmup Iteration   3: 9.278 ops/ms
Iteration   1: 9.439 ops/ms
Iteration   2: 9.475 ops/ms
Iteration   3: 9.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.428 ±(99.9%) 0.970 ops/ms [Average]
  (min, avg, max) = (9.370, 9.428, 9.475), stdev = 0.053
  CI (99.9%): [8.458, 10.398] (assumes normal distribution)


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
# Warmup Iteration   1: 5.681 ops/ms
# Warmup Iteration   2: 8.370 ops/ms
# Warmup Iteration   3: 8.593 ops/ms
Iteration   1: 9.001 ops/ms
Iteration   2: 8.664 ops/ms
Iteration   3: 8.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.847 ±(99.9%) 3.103 ops/ms [Average]
  (min, avg, max) = (8.664, 8.847, 9.001), stdev = 0.170
  CI (99.9%): [5.743, 11.950] (assumes normal distribution)


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
# Warmup Iteration   1: 4.972 ops/ms
# Warmup Iteration   2: 6.050 ops/ms
# Warmup Iteration   3: 6.738 ops/ms
Iteration   1: 6.962 ops/ms
Iteration   2: 6.858 ops/ms
Iteration   3: 7.028 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.949 ±(99.9%) 1.570 ops/ms [Average]
  (min, avg, max) = (6.858, 6.949, 7.028), stdev = 0.086
  CI (99.9%): [5.379, 8.519] (assumes normal distribution)


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
# Warmup Iteration   1: 5.150 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.016 ms/op
Iteration   1: 3.625 ±(99.9%) 0.005 ms/op
Iteration   2: 3.553 ±(99.9%) 0.002 ms/op
Iteration   3: 3.555 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.578 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.553, 3.578, 3.625), stdev = 0.041
  CI (99.9%): [2.827, 4.328] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.800 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.600 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.004 ms/op
Iteration   1: 3.411 ±(99.9%) 0.004 ms/op
Iteration   2: 3.475 ±(99.9%) 0.003 ms/op
Iteration   3: 3.357 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.414 ±(99.9%) 1.081 ms/op [Average]
  (min, avg, max) = (3.357, 3.414, 3.475), stdev = 0.059
  CI (99.9%): [2.333, 4.495] (assumes normal distribution)


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
# Warmup Iteration   1: 5.038 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.883 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.003 ms/op
Iteration   1: 3.511 ±(99.9%) 0.006 ms/op
Iteration   2: 3.639 ±(99.9%) 0.004 ms/op
Iteration   3: 3.587 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.579 ±(99.9%) 1.176 ms/op [Average]
  (min, avg, max) = (3.511, 3.579, 3.639), stdev = 0.064
  CI (99.9%): [2.403, 4.755] (assumes normal distribution)


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
# Warmup Iteration   1: 7.279 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.799 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.652 ±(99.9%) 0.013 ms/op
Iteration   1: 4.643 ±(99.9%) 0.011 ms/op
Iteration   2: 4.536 ±(99.9%) 0.033 ms/op
Iteration   3: 4.635 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.605 ±(99.9%) 1.085 ms/op [Average]
  (min, avg, max) = (4.536, 4.605, 4.643), stdev = 0.059
  CI (99.9%): [3.519, 5.690] (assumes normal distribution)


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
# Warmup Iteration   1: 5.487 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.606 ±(99.9%) 0.009 ms/op
Iteration   1: 3.516 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.888 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.043 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.300 ms/op
                 createUser·p0.999:  8.701 ms/op
                 createUser·p0.9999: 30.537 ms/op
                 createUser·p1.00:   31.031 ms/op

Iteration   2: 3.531 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.177 ms/op
                 createUser·p0.999:  10.306 ms/op
                 createUser·p0.9999: 20.939 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   3: 3.542 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.071 ms/op
                 createUser·p0.95:   4.489 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  16.440 ms/op
                 createUser·p0.9999: 23.329 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 271946
  mean =      3.529 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10519 
    [ 2.500,  5.000) = 256940 
    [ 5.000,  7.500) = 3854 
    [ 7.500, 10.000) = 369 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 13 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.431 ms/op
     p(99.9000) =      9.880 ms/op
     p(99.9900) =     29.616 ms/op
     p(99.9990) =     30.942 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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
# Warmup Iteration   1: 4.911 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.567 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.438 ±(99.9%) 0.006 ms/op
Iteration   1: 3.400 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.942 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  7.796 ms/op
                 existUser·p0.9999: 21.089 ms/op
                 existUser·p1.00:   21.332 ms/op

Iteration   2: 3.476 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.768 ms/op
                 existUser·p0.50:   3.445 ms/op
                 existUser·p0.90:   4.137 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  7.281 ms/op
                 existUser·p0.9999: 16.770 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   3: 3.389 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   3.981 ms/op
                 existUser·p0.95:   4.194 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  12.567 ms/op
                 existUser·p0.9999: 20.021 ms/op
                 existUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280873
  mean =      3.421 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11909 
    [ 2.500,  5.000) = 265318 
    [ 5.000,  7.500) = 3193 
    [ 7.500, 10.000) = 162 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.768 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     10.719 ms/op
     p(99.9900) =     20.838 ms/op
     p(99.9990) =     21.266 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


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
# Warmup Iteration   1: 5.448 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.858 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.009 ms/op
Iteration   1: 3.597 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.174 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.562 ms/op
                 getUser·p0.999:  12.190 ms/op
                 getUser·p0.9999: 14.665 ms/op
                 getUser·p1.00:   14.811 ms/op

Iteration   2: 3.567 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.527 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  10.600 ms/op
                 getUser·p0.9999: 16.139 ms/op
                 getUser·p1.00:   16.433 ms/op

Iteration   3: 3.660 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   3.588 ms/op
                 getUser·p0.90:   4.317 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  9.683 ms/op
                 getUser·p0.9999: 19.907 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 266108
  mean =      3.608 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3569 
    [ 2.500,  5.000) = 257413 
    [ 5.000,  7.500) = 4373 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.157 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     10.879 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     20.175 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 6.051 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.029 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.640 ±(99.9%) 0.014 ms/op
Iteration   1: 4.647 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.552 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  15.825 ms/op
                 listUser·p0.9999: 19.308 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   2: 4.664 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.807 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  15.277 ms/op
                 listUser·p0.9999: 19.169 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 4.639 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   8.208 ms/op
                 listUser·p0.999:  18.648 ms/op
                 listUser·p0.9999: 34.217 ms/op
                 listUser·p1.00:   34.800 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206326
  mean =      4.650 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 407 
    [ 2.500,  5.000) = 165043 
    [ 5.000,  7.500) = 35796 
    [ 7.500, 10.000) = 4242 
    [10.000, 12.500) = 402 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.717 ms/op
     p(99.0000) =      8.503 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     32.628 ms/op
     p(99.9990) =     34.660 ms/op
     p(99.9999) =     34.800 ms/op
    p(100.0000) =     34.800 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.847 ± 1.166  ops/ms
ClientGrpc.existUser                       thrpt       3   9.428 ± 0.970  ops/ms
ClientGrpc.getUser                         thrpt       3   8.847 ± 3.103  ops/ms
ClientGrpc.listUser                        thrpt       3   6.949 ± 1.570  ops/ms
ClientGrpc.createUser                       avgt       3   3.578 ± 0.750   ms/op
ClientGrpc.existUser                        avgt       3   3.414 ± 1.081   ms/op
ClientGrpc.getUser                          avgt       3   3.579 ± 1.176   ms/op
ClientGrpc.listUser                         avgt       3   4.605 ± 1.085   ms/op
ClientGrpc.createUser                     sample  271946   3.529 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.112           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.431           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.880           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.616           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.031           ms/op
ClientGrpc.existUser                      sample  280873   3.421 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.768           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.035           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.719           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.838           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.332           ms/op
ClientGrpc.getUser                        sample  266108   3.608 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.039           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.547           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.157           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.505           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.879           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.235           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.677           ms/op
ClientGrpc.listUser                       sample  206326   4.650 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.931           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.503           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.450           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.628           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.800           ms/op
