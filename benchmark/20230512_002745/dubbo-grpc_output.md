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
# Warmup Iteration   1: 3.142 ops/ms
# Warmup Iteration   2: 6.661 ops/ms
# Warmup Iteration   3: 7.953 ops/ms
Iteration   1: 8.593 ops/ms
Iteration   2: 8.548 ops/ms
Iteration   3: 8.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.627 ±(99.9%) 1.854 ops/ms [Average]
  (min, avg, max) = (8.548, 8.627, 8.742), stdev = 0.102
  CI (99.9%): [6.773, 10.482] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.616 ops/ms
# Warmup Iteration   2: 8.807 ops/ms
# Warmup Iteration   3: 9.122 ops/ms
Iteration   1: 9.302 ops/ms
Iteration   2: 9.455 ops/ms
Iteration   3: 9.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.412 ±(99.9%) 1.759 ops/ms [Average]
  (min, avg, max) = (9.302, 9.412, 9.480), stdev = 0.096
  CI (99.9%): [7.653, 11.171] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.795 ops/ms
# Warmup Iteration   2: 7.978 ops/ms
# Warmup Iteration   3: 8.485 ops/ms
Iteration   1: 8.784 ops/ms
Iteration   2: 8.615 ops/ms
Iteration   3: 8.351 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.583 ±(99.9%) 3.989 ops/ms [Average]
  (min, avg, max) = (8.351, 8.583, 8.784), stdev = 0.219
  CI (99.9%): [4.595, 12.572] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.817 ops/ms
# Warmup Iteration   2: 6.365 ops/ms
# Warmup Iteration   3: 6.646 ops/ms
Iteration   1: 6.701 ops/ms
Iteration   2: 6.764 ops/ms
Iteration   3: 6.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.708 ±(99.9%) 0.975 ops/ms [Average]
  (min, avg, max) = (6.658, 6.708, 6.764), stdev = 0.053
  CI (99.9%): [5.733, 7.683] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.601 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.742 ±(99.9%) 0.012 ms/op
Iteration   1: 3.732 ±(99.9%) 0.003 ms/op
Iteration   2: 3.732 ±(99.9%) 0.003 ms/op
Iteration   3: 3.555 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.673 ±(99.9%) 1.861 ms/op [Average]
  (min, avg, max) = (3.555, 3.673, 3.732), stdev = 0.102
  CI (99.9%): [1.812, 5.534] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.253 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.596 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.004 ms/op
Iteration   1: 3.465 ±(99.9%) 0.004 ms/op
Iteration   2: 3.453 ±(99.9%) 0.003 ms/op
Iteration   3: 3.453 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.457 ±(99.9%) 0.122 ms/op [Average]
  (min, avg, max) = (3.453, 3.457, 3.465), stdev = 0.007
  CI (99.9%): [3.335, 3.579] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.334 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 3.945 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 3.741 ±(99.9%) 0.006 ms/op
Iteration   1: 3.670 ±(99.9%) 0.004 ms/op
Iteration   2: 3.624 ±(99.9%) 0.004 ms/op
Iteration   3: 3.673 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.656 ±(99.9%) 0.503 ms/op [Average]
  (min, avg, max) = (3.624, 3.656, 3.673), stdev = 0.028
  CI (99.9%): [3.153, 4.158] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.016 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.825 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.728 ±(99.9%) 0.017 ms/op
Iteration   1: 4.842 ±(99.9%) 0.008 ms/op
Iteration   2: 4.704 ±(99.9%) 0.012 ms/op
Iteration   3: 4.579 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.708 ±(99.9%) 2.394 ms/op [Average]
  (min, avg, max) = (4.579, 4.708, 4.842), stdev = 0.131
  CI (99.9%): [2.315, 7.102] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.461 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.874 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.008 ms/op
Iteration   1: 3.673 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.057 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.792 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  13.396 ms/op
                 createUser·p0.9999: 22.990 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.707 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.836 ms/op
                 createUser·p0.50:   3.645 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  12.546 ms/op
                 createUser·p0.9999: 16.341 ms/op
                 createUser·p1.00:   16.761 ms/op

Iteration   3: 3.669 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  10.235 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260489
  mean =      3.683 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6894 
    [ 2.500,  5.000) = 245077 
    [ 5.000,  7.500) = 7701 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     11.199 ms/op
     p(99.9900) =     22.212 ms/op
     p(99.9990) =     24.287 ms/op
     p(99.9999) =     24.445 ms/op
    p(100.0000) =     24.445 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.178 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.729 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.582 ±(99.9%) 0.008 ms/op
Iteration   1: 3.473 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  9.696 ms/op
                 existUser·p0.9999: 17.491 ms/op
                 existUser·p1.00:   18.088 ms/op

Iteration   2: 3.414 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   3.367 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  8.684 ms/op
                 existUser·p0.9999: 16.192 ms/op
                 existUser·p1.00:   16.843 ms/op

Iteration   3: 3.467 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.481 ms/op
                 existUser·p0.99:   6.152 ms/op
                 existUser·p0.999:  11.027 ms/op
                 existUser·p0.9999: 18.601 ms/op
                 existUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 278185
  mean =      3.451 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 160 
    [ 1.250,  2.500) = 7430 
    [ 2.500,  3.750) = 214158 
    [ 3.750,  5.000) = 50463 
    [ 5.000,  6.250) = 3953 
    [ 6.250,  7.500) = 1083 
    [ 7.500,  8.750) = 454 
    [ 8.750, 10.000) = 198 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.047 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.792 ms/op
     p(99.9000) =     10.040 ms/op
     p(99.9900) =     17.897 ms/op
     p(99.9990) =     19.235 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.408 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.010 ms/op
Iteration   1: 3.644 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.760 ms/op
                 getUser·p0.99:   6.352 ms/op
                 getUser·p0.999:  9.257 ms/op
                 getUser·p0.9999: 13.348 ms/op
                 getUser·p1.00:   13.681 ms/op

Iteration   2: 3.747 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.564 ms/op
                 getUser·p0.999:  11.715 ms/op
                 getUser·p0.9999: 16.342 ms/op
                 getUser·p1.00:   16.613 ms/op

Iteration   3: 3.698 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.853 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.078 ms/op
                 getUser·p0.999:  9.766 ms/op
                 getUser·p0.9999: 18.022 ms/op
                 getUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259703
  mean =      3.696 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6193 
    [ 2.500,  5.000) = 243624 
    [ 5.000,  7.500) = 8924 
    [ 7.500, 10.000) = 693 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.853 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     10.093 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     20.311 ms/op
     p(99.9999) =     20.742 ms/op
    p(100.0000) =     20.742 ms/op


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
# Warmup Iteration   1: 6.780 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.989 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.808 ±(99.9%) 0.016 ms/op
Iteration   1: 4.585 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   6.078 ms/op
                 listUser·p0.95:   7.012 ms/op
                 listUser·p0.99:   8.658 ms/op
                 listUser·p0.999:  17.072 ms/op
                 listUser·p0.9999: 22.265 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 4.915 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   6.545 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  24.510 ms/op
                 listUser·p0.9999: 28.245 ms/op
                 listUser·p1.00:   28.508 ms/op

Iteration   3: 4.841 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.504 ms/op
                 listUser·p0.95:   7.332 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 21.718 ms/op
                 listUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200912
  mean =      4.776 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 892 
    [ 2.500,  5.000) = 141037 
    [ 5.000,  7.500) = 51227 
    [ 7.500, 10.000) = 6583 
    [10.000, 12.500) = 642 
    [12.500, 15.000) = 144 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      4.489 ms/op
     p(90.0000) =      6.398 ms/op
     p(95.0000) =      7.217 ms/op
     p(99.0000) =      9.060 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     27.242 ms/op
     p(99.9990) =     28.442 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.627 ± 1.854  ops/ms
ClientGrpc.existUser                       thrpt       3   9.412 ± 1.759  ops/ms
ClientGrpc.getUser                         thrpt       3   8.583 ± 3.989  ops/ms
ClientGrpc.listUser                        thrpt       3   6.708 ± 0.975  ops/ms
ClientGrpc.createUser                       avgt       3   3.673 ± 1.861   ms/op
ClientGrpc.existUser                        avgt       3   3.457 ± 0.122   ms/op
ClientGrpc.getUser                          avgt       3   3.656 ± 0.503   ms/op
ClientGrpc.listUser                         avgt       3   4.708 ± 2.394   ms/op
ClientGrpc.createUser                     sample  260489   3.683 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.836           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.882           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.199           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.212           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.445           ms/op
ClientGrpc.existUser                      sample  278185   3.451 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.800           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.379           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.047           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.792           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.040           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.897           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.333           ms/op
ClientGrpc.getUser                        sample  259703   3.696 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.853           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.308           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.093           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.564           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.742           ms/op
ClientGrpc.listUser                       sample  200912   4.776 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.145           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.489           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.398           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.217           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.060           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.268           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.242           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.508           ms/op
