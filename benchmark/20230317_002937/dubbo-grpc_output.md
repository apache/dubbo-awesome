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
# Warmup Iteration   1: 3.149 ops/ms
# Warmup Iteration   2: 6.973 ops/ms
# Warmup Iteration   3: 8.428 ops/ms
Iteration   1: 8.570 ops/ms
Iteration   2: 8.931 ops/ms
Iteration   3: 8.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.692 ±(99.9%) 3.762 ops/ms [Average]
  (min, avg, max) = (8.570, 8.692, 8.931), stdev = 0.206
  CI (99.9%): [4.931, 12.454] (assumes normal distribution)


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
# Warmup Iteration   1: 6.024 ops/ms
# Warmup Iteration   2: 8.550 ops/ms
# Warmup Iteration   3: 9.062 ops/ms
Iteration   1: 9.201 ops/ms
Iteration   2: 9.259 ops/ms
Iteration   3: 9.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.309 ±(99.9%) 2.546 ops/ms [Average]
  (min, avg, max) = (9.201, 9.309, 9.466), stdev = 0.140
  CI (99.9%): [6.763, 11.854] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.266 ops/ms
# Warmup Iteration   2: 8.164 ops/ms
# Warmup Iteration   3: 8.262 ops/ms
Iteration   1: 8.573 ops/ms
Iteration   2: 8.793 ops/ms
Iteration   3: 8.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.773 ±(99.9%) 3.484 ops/ms [Average]
  (min, avg, max) = (8.573, 8.773, 8.954), stdev = 0.191
  CI (99.9%): [5.289, 12.258] (assumes normal distribution)


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
# Warmup Iteration   1: 5.036 ops/ms
# Warmup Iteration   2: 5.983 ops/ms
# Warmup Iteration   3: 6.673 ops/ms
Iteration   1: 6.676 ops/ms
Iteration   2: 6.569 ops/ms
Iteration   3: 6.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.607 ±(99.9%) 1.083 ops/ms [Average]
  (min, avg, max) = (6.569, 6.607, 6.676), stdev = 0.059
  CI (99.9%): [5.524, 7.690] (assumes normal distribution)


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
# Warmup Iteration   1: 5.150 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.590 ±(99.9%) 0.003 ms/op
Iteration   1: 3.564 ±(99.9%) 0.045 ms/op
Iteration   2: 3.658 ±(99.9%) 0.002 ms/op
Iteration   3: 3.620 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.614 ±(99.9%) 0.857 ms/op [Average]
  (min, avg, max) = (3.564, 3.614, 3.658), stdev = 0.047
  CI (99.9%): [2.757, 4.471] (assumes normal distribution)


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
# Warmup Iteration   1: 4.839 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.004 ms/op
Iteration   1: 3.477 ±(99.9%) 0.003 ms/op
Iteration   2: 3.375 ±(99.9%) 0.003 ms/op
Iteration   3: 3.435 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.429 ±(99.9%) 0.939 ms/op [Average]
  (min, avg, max) = (3.375, 3.429, 3.477), stdev = 0.051
  CI (99.9%): [2.491, 4.368] (assumes normal distribution)


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
# Warmup Iteration   1: 5.193 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.004 ms/op
Iteration   1: 3.571 ±(99.9%) 0.005 ms/op
Iteration   2: 3.607 ±(99.9%) 0.003 ms/op
Iteration   3: 3.543 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.574 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (3.543, 3.574, 3.607), stdev = 0.032
  CI (99.9%): [2.981, 4.167] (assumes normal distribution)


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
# Warmup Iteration   1: 6.324 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.017 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.780 ±(99.9%) 0.018 ms/op
Iteration   1: 4.851 ±(99.9%) 0.010 ms/op
Iteration   2: 4.696 ±(99.9%) 0.014 ms/op
Iteration   3: 4.702 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.750 ±(99.9%) 1.605 ms/op [Average]
  (min, avg, max) = (4.696, 4.750, 4.851), stdev = 0.088
  CI (99.9%): [3.145, 6.354] (assumes normal distribution)


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
# Warmup Iteration   1: 4.996 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.689 ±(99.9%) 0.009 ms/op
Iteration   1: 3.599 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.983 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  8.721 ms/op
                 createUser·p0.9999: 14.456 ms/op
                 createUser·p1.00:   14.729 ms/op

Iteration   2: 3.645 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.011 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.604 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  9.191 ms/op
                 createUser·p0.9999: 15.585 ms/op
                 createUser·p1.00:   15.843 ms/op

Iteration   3: 3.658 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.824 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   5.798 ms/op
                 createUser·p0.999:  12.468 ms/op
                 createUser·p0.9999: 21.930 ms/op
                 createUser·p1.00:   22.348 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264129
  mean =      3.634 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5381 
    [ 2.500,  5.000) = 251958 
    [ 5.000,  7.500) = 6103 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =      9.716 ms/op
     p(99.9900) =     19.385 ms/op
     p(99.9990) =     22.315 ms/op
     p(99.9999) =     22.348 ms/op
    p(100.0000) =     22.348 ms/op


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
# Warmup Iteration   1: 4.718 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.008 ms/op
Iteration   1: 3.368 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.953 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  7.454 ms/op
                 existUser·p0.9999: 19.874 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   2: 3.490 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  11.111 ms/op
                 existUser·p0.9999: 17.760 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   3: 3.388 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.104 ms/op
                 existUser·p0.999:  7.135 ms/op
                 existUser·p0.9999: 18.997 ms/op
                 existUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 281171
  mean =      3.415 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8827 
    [ 2.500,  5.000) = 268410 
    [ 5.000,  7.500) = 3495 
    [ 7.500, 10.000) = 251 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     18.641 ms/op
     p(99.9990) =     20.111 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 5.323 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.958 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.678 ±(99.9%) 0.008 ms/op
Iteration   1: 3.637 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.868 ms/op
                 getUser·p0.50:   3.568 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.735 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 19.726 ms/op
                 getUser·p1.00:   20.283 ms/op

Iteration   2: 3.595 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   3.535 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.095 ms/op
                 getUser·p0.999:  8.114 ms/op
                 getUser·p0.9999: 20.614 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   3: 3.608 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.522 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  8.958 ms/op
                 getUser·p0.9999: 24.744 ms/op
                 getUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 265645
  mean =      3.613 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5843 
    [ 2.500,  5.000) = 253951 
    [ 5.000,  7.500) = 5117 
    [ 7.500, 10.000) = 487 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =      9.601 ms/op
     p(99.9900) =     23.898 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 5.870 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.102 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.736 ±(99.9%) 0.014 ms/op
Iteration   1: 4.690 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   18.809 ms/op

Iteration   2: 4.648 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   5.579 ms/op
                 listUser·p0.95:   6.472 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  17.406 ms/op
                 listUser·p0.9999: 21.162 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 4.584 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.580 ms/op
                 listUser·p0.95:   6.390 ms/op
                 listUser·p0.99:   8.298 ms/op
                 listUser·p0.999:  19.865 ms/op
                 listUser·p0.9999: 30.999 ms/op
                 listUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206783
  mean =      4.640 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 320 
    [ 2.500,  5.000) = 166216 
    [ 5.000,  7.500) = 35851 
    [ 7.500, 10.000) = 3625 
    [10.000, 12.500) = 418 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.895 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.710 ms/op
     p(95.0000) =      6.537 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     30.409 ms/op
     p(99.9990) =     31.359 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.692 ± 3.762  ops/ms
ClientGrpc.existUser                       thrpt       3   9.309 ± 2.546  ops/ms
ClientGrpc.getUser                         thrpt       3   8.773 ± 3.484  ops/ms
ClientGrpc.listUser                        thrpt       3   6.607 ± 1.083  ops/ms
ClientGrpc.createUser                       avgt       3   3.614 ± 0.857   ms/op
ClientGrpc.existUser                        avgt       3   3.429 ± 0.939   ms/op
ClientGrpc.getUser                          avgt       3   3.574 ± 0.593   ms/op
ClientGrpc.listUser                         avgt       3   4.750 ± 1.605   ms/op
ClientGrpc.createUser                     sample  264129   3.634 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.824           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.620           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.716           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.385           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.348           ms/op
ClientGrpc.existUser                      sample  281171   3.415 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.730           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.387           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.333           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.552           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.641           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  265645   3.613 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.868           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.555           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.601           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.898           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.936           ms/op
ClientGrpc.listUser                       sample  206783   4.640 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.895           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.710           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.372           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.138           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.409           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.392           ms/op
