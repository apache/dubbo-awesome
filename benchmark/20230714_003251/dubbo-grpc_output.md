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
# Warmup Iteration   1: 2.929 ops/ms
# Warmup Iteration   2: 6.806 ops/ms
# Warmup Iteration   3: 7.737 ops/ms
Iteration   1: 8.355 ops/ms
Iteration   2: 8.439 ops/ms
Iteration   3: 8.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.451 ±(99.9%) 1.879 ops/ms [Average]
  (min, avg, max) = (8.355, 8.451, 8.560), stdev = 0.103
  CI (99.9%): [6.572, 10.330] (assumes normal distribution)


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
# Warmup Iteration   1: 5.737 ops/ms
# Warmup Iteration   2: 8.124 ops/ms
# Warmup Iteration   3: 8.502 ops/ms
Iteration   1: 8.807 ops/ms
Iteration   2: 9.442 ops/ms
Iteration   3: 9.036 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.095 ±(99.9%) 5.866 ops/ms [Average]
  (min, avg, max) = (8.807, 9.095, 9.442), stdev = 0.322
  CI (99.9%): [3.229, 14.961] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.137 ops/ms
# Warmup Iteration   2: 8.037 ops/ms
# Warmup Iteration   3: 8.298 ops/ms
Iteration   1: 8.274 ops/ms
Iteration   2: 8.457 ops/ms
Iteration   3: 8.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.407 ±(99.9%) 2.118 ops/ms [Average]
  (min, avg, max) = (8.274, 8.407, 8.489), stdev = 0.116
  CI (99.9%): [6.289, 10.524] (assumes normal distribution)


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
# Warmup Iteration   1: 4.599 ops/ms
# Warmup Iteration   2: 5.733 ops/ms
# Warmup Iteration   3: 6.551 ops/ms
Iteration   1: 6.426 ops/ms
Iteration   2: 6.365 ops/ms
Iteration   3: 6.661 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.484 ±(99.9%) 2.849 ops/ms [Average]
  (min, avg, max) = (6.365, 6.484, 6.661), stdev = 0.156
  CI (99.9%): [3.635, 9.333] (assumes normal distribution)


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
# Warmup Iteration   1: 5.773 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 3.923 ±(99.9%) 0.005 ms/op
Iteration   1: 3.882 ±(99.9%) 0.003 ms/op
Iteration   2: 3.750 ±(99.9%) 0.004 ms/op
Iteration   3: 3.775 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.802 ±(99.9%) 1.276 ms/op [Average]
  (min, avg, max) = (3.750, 3.802, 3.882), stdev = 0.070
  CI (99.9%): [2.527, 5.078] (assumes normal distribution)


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
# Warmup Iteration   1: 5.011 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.007 ms/op
Iteration   1: 3.555 ±(99.9%) 0.004 ms/op
Iteration   2: 3.545 ±(99.9%) 0.003 ms/op
Iteration   3: 3.554 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.551 ±(99.9%) 0.104 ms/op [Average]
  (min, avg, max) = (3.545, 3.551, 3.555), stdev = 0.006
  CI (99.9%): [3.448, 3.655] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.383 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.845 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.003 ms/op
Iteration   1: 3.709 ±(99.9%) 0.005 ms/op
Iteration   2: 3.741 ±(99.9%) 0.004 ms/op
Iteration   3: 3.813 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.754 ±(99.9%) 0.970 ms/op [Average]
  (min, avg, max) = (3.709, 3.754, 3.813), stdev = 0.053
  CI (99.9%): [2.784, 4.724] (assumes normal distribution)


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
# Warmup Iteration   1: 6.749 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.304 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.039 ±(99.9%) 0.019 ms/op
Iteration   1: 4.817 ±(99.9%) 0.013 ms/op
Iteration   2: 4.884 ±(99.9%) 0.016 ms/op
Iteration   3: 4.890 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.864 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (4.817, 4.864, 4.890), stdev = 0.040
  CI (99.9%): [4.128, 5.600] (assumes normal distribution)


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
# Warmup Iteration   1: 5.647 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.010 ms/op
Iteration   1: 3.768 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  8.897 ms/op
                 createUser·p0.9999: 15.409 ms/op
                 createUser·p1.00:   16.056 ms/op

Iteration   2: 3.735 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.991 ms/op
                 createUser·p0.50:   3.621 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  12.294 ms/op
                 createUser·p0.9999: 22.675 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 3.673 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.949 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   5.964 ms/op
                 createUser·p0.999:  13.919 ms/op
                 createUser·p0.9999: 21.800 ms/op
                 createUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 257744
  mean =      3.725 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4513 
    [ 2.500,  5.000) = 241944 
    [ 5.000,  7.500) = 10385 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     21.838 ms/op
     p(99.9990) =     23.040 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 4.739 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.008 ms/op
Iteration   1: 3.518 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.858 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  12.500 ms/op
                 existUser·p0.9999: 19.100 ms/op
                 existUser·p1.00:   20.120 ms/op

Iteration   2: 3.594 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  8.980 ms/op
                 existUser·p0.9999: 19.628 ms/op
                 existUser·p1.00:   19.923 ms/op

Iteration   3: 3.572 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  10.869 ms/op
                 existUser·p0.9999: 21.273 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269498
  mean =      3.561 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10200 
    [ 2.500,  5.000) = 250881 
    [ 5.000,  7.500) = 7285 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =     10.347 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     21.755 ms/op
     p(99.9999) =     22.086 ms/op
    p(100.0000) =     22.086 ms/op


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
# Warmup Iteration   1: 5.142 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.009 ms/op
Iteration   1: 3.747 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.059 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   6.296 ms/op
                 getUser·p0.999:  9.999 ms/op
                 getUser·p0.9999: 21.118 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   2: 3.811 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  10.289 ms/op
                 getUser·p0.9999: 17.321 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   3: 3.716 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.973 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  8.994 ms/op
                 getUser·p0.9999: 21.345 ms/op
                 getUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 255348
  mean =      3.757 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7092 
    [ 2.500,  5.000) = 237169 
    [ 5.000,  7.500) = 10103 
    [ 7.500, 10.000) = 720 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     10.054 ms/op
     p(99.9900) =     21.070 ms/op
     p(99.9990) =     22.061 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 6.283 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.242 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.804 ±(99.9%) 0.015 ms/op
Iteration   1: 4.772 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.661 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   7.004 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  15.990 ms/op
                 listUser·p0.9999: 17.419 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   2: 4.937 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.382 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.283 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  16.997 ms/op
                 listUser·p0.9999: 19.400 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   3: 4.924 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.303 ms/op
                 listUser·p0.50:   4.579 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.455 ms/op
                 listUser·p0.99:   9.159 ms/op
                 listUser·p0.999:  26.774 ms/op
                 listUser·p0.9999: 33.522 ms/op
                 listUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 196783
  mean =      4.877 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 340 
    [ 2.500,  5.000) = 136935 
    [ 5.000,  7.500) = 51752 
    [ 7.500, 10.000) = 6792 
    [10.000, 12.500) = 526 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.303 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      6.357 ms/op
     p(95.0000) =      7.242 ms/op
     p(99.0000) =      9.028 ms/op
     p(99.9000) =     17.400 ms/op
     p(99.9900) =     32.877 ms/op
     p(99.9990) =     34.106 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.451 ± 1.879  ops/ms
ClientGrpc.existUser                       thrpt       3   9.095 ± 5.866  ops/ms
ClientGrpc.getUser                         thrpt       3   8.407 ± 2.118  ops/ms
ClientGrpc.listUser                        thrpt       3   6.484 ± 2.849  ops/ms
ClientGrpc.createUser                       avgt       3   3.802 ± 1.276   ms/op
ClientGrpc.existUser                        avgt       3   3.551 ± 0.104   ms/op
ClientGrpc.getUser                          avgt       3   3.754 ± 0.970   ms/op
ClientGrpc.listUser                         avgt       3   4.864 ± 0.736   ms/op
ClientGrpc.createUser                     sample  257744   3.725 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.716           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.915           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.250           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.075           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.838           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.495           ms/op
ClientGrpc.existUser                      sample  269498   3.561 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.843           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.160           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.347           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.792           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.086           ms/op
ClientGrpc.getUser                        sample  255348   3.757 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.834           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.522           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.915           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.259           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.054           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.070           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.938           ms/op
ClientGrpc.listUser                       sample  196783   4.877 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.303           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.357           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.242           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.028           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.400           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.877           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.931           ms/op
