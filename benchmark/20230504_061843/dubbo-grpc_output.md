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
# Warmup Iteration   1: 2.922 ops/ms
# Warmup Iteration   2: 6.856 ops/ms
# Warmup Iteration   3: 8.457 ops/ms
Iteration   1: 8.530 ops/ms
Iteration   2: 9.045 ops/ms
Iteration   3: 8.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.773 ±(99.9%) 4.717 ops/ms [Average]
  (min, avg, max) = (8.530, 8.773, 9.045), stdev = 0.259
  CI (99.9%): [4.056, 13.491] (assumes normal distribution)


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
# Warmup Iteration   1: 5.709 ops/ms
# Warmup Iteration   2: 8.808 ops/ms
# Warmup Iteration   3: 8.989 ops/ms
Iteration   1: 9.268 ops/ms
Iteration   2: 9.194 ops/ms
Iteration   3: 9.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.273 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (9.194, 9.273, 9.357), stdev = 0.082
  CI (99.9%): [7.783, 10.762] (assumes normal distribution)


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
# Warmup Iteration   1: 4.930 ops/ms
# Warmup Iteration   2: 8.322 ops/ms
# Warmup Iteration   3: 8.539 ops/ms
Iteration   1: 8.406 ops/ms
Iteration   2: 8.841 ops/ms
Iteration   3: 8.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.620 ±(99.9%) 3.974 ops/ms [Average]
  (min, avg, max) = (8.406, 8.620, 8.841), stdev = 0.218
  CI (99.9%): [4.646, 12.594] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.224 ops/ms
# Warmup Iteration   2: 6.388 ops/ms
# Warmup Iteration   3: 6.518 ops/ms
Iteration   1: 6.524 ops/ms
Iteration   2: 6.661 ops/ms
Iteration   3: 6.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.623 ±(99.9%) 1.579 ops/ms [Average]
  (min, avg, max) = (6.524, 6.623, 6.684), stdev = 0.087
  CI (99.9%): [5.044, 8.202] (assumes normal distribution)


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
# Warmup Iteration   1: 5.702 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.753 ±(99.9%) 0.038 ms/op
Iteration   1: 3.674 ±(99.9%) 0.004 ms/op
Iteration   2: 3.632 ±(99.9%) 0.004 ms/op
Iteration   3: 3.696 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.668 ±(99.9%) 0.597 ms/op [Average]
  (min, avg, max) = (3.632, 3.668, 3.696), stdev = 0.033
  CI (99.9%): [3.071, 4.264] (assumes normal distribution)


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
# Warmup Iteration   1: 5.151 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.552 ±(99.9%) 0.004 ms/op
Iteration   1: 3.523 ±(99.9%) 0.002 ms/op
Iteration   2: 3.456 ±(99.9%) 0.004 ms/op
Iteration   3: 3.450 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.476 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (3.450, 3.476, 3.523), stdev = 0.040
  CI (99.9%): [2.742, 4.210] (assumes normal distribution)


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
# Warmup Iteration   1: 5.306 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.004 ms/op
Iteration   1: 3.778 ±(99.9%) 0.004 ms/op
Iteration   2: 3.788 ±(99.9%) 0.005 ms/op
Iteration   3: 3.664 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.743 ±(99.9%) 1.261 ms/op [Average]
  (min, avg, max) = (3.664, 3.743, 3.788), stdev = 0.069
  CI (99.9%): [2.482, 5.004] (assumes normal distribution)


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
# Warmup Iteration   1: 5.936 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.166 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.873 ±(99.9%) 0.018 ms/op
Iteration   1: 4.845 ±(99.9%) 0.008 ms/op
Iteration   2: 4.717 ±(99.9%) 0.014 ms/op
Iteration   3: 4.784 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.782 ±(99.9%) 1.166 ms/op [Average]
  (min, avg, max) = (4.717, 4.782, 4.845), stdev = 0.064
  CI (99.9%): [3.616, 5.948] (assumes normal distribution)


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
# Warmup Iteration   1: 5.591 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.009 ms/op
Iteration   1: 3.787 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  11.317 ms/op
                 createUser·p0.9999: 17.301 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   2: 3.615 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  8.886 ms/op
                 createUser·p0.9999: 20.190 ms/op
                 createUser·p1.00:   20.808 ms/op

Iteration   3: 3.696 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.623 ms/op
                 createUser·p0.90:   4.325 ms/op
                 createUser·p0.95:   4.612 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  16.769 ms/op
                 createUser·p0.9999: 20.405 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259466
  mean =      3.698 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3700 
    [ 2.500,  5.000) = 249178 
    [ 5.000,  7.500) = 5703 
    [ 7.500, 10.000) = 544 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     12.249 ms/op
     p(99.9900) =     20.187 ms/op
     p(99.9990) =     20.755 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 5.240 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.788 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.009 ms/op
Iteration   1: 3.490 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.088 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  7.905 ms/op
                 existUser·p0.9999: 21.785 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   2: 3.514 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   3.469 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  11.780 ms/op
                 existUser·p0.9999: 16.349 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   3: 3.490 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  10.901 ms/op
                 existUser·p0.9999: 20.802 ms/op
                 existUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274553
  mean =      3.498 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7131 
    [ 2.500,  5.000) = 263544 
    [ 5.000,  7.500) = 3323 
    [ 7.500, 10.000) = 237 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.886 ms/op
     p(50.0000) =      3.457 ms/op
     p(90.0000) =      4.039 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =     11.132 ms/op
     p(99.9900) =     21.055 ms/op
     p(99.9990) =     22.553 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 5.101 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.011 ms/op
Iteration   1: 3.747 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.674 ms/op
                 getUser·p0.90:   4.481 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 23.850 ms/op
                 getUser·p1.00:   24.445 ms/op

Iteration   2: 3.733 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.083 ms/op
                 getUser·p0.50:   3.662 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  8.375 ms/op
                 getUser·p0.9999: 22.390 ms/op
                 getUser·p1.00:   22.807 ms/op

Iteration   3: 3.617 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.911 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   5.620 ms/op
                 getUser·p0.999:  9.126 ms/op
                 getUser·p0.9999: 25.765 ms/op
                 getUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259430
  mean =      3.698 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6345 
    [ 2.500,  5.000) = 246221 
    [ 5.000,  7.500) = 6185 
    [ 7.500, 10.000) = 501 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.911 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     25.037 ms/op
     p(99.9990) =     26.765 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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
# Warmup Iteration   1: 7.689 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.195 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.814 ±(99.9%) 0.014 ms/op
Iteration   1: 4.886 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.665 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   6.758 ms/op
                 listUser·p0.99:   8.607 ms/op
                 listUser·p0.999:  17.512 ms/op
                 listUser·p0.9999: 21.284 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 4.678 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.798 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  16.065 ms/op
                 listUser·p0.9999: 20.346 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 4.911 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   6.930 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 21.903 ms/op
                 listUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199260
  mean =      4.823 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 498 
    [ 2.500,  5.000) = 142083 
    [ 5.000,  7.500) = 51316 
    [ 7.500, 10.000) = 4609 
    [10.000, 12.500) = 413 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.798 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      6.111 ms/op
     p(95.0000) =      6.816 ms/op
     p(99.0000) =      8.651 ms/op
     p(99.9000) =     17.195 ms/op
     p(99.9900) =     21.400 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.773 ± 4.717  ops/ms
ClientGrpc.existUser                       thrpt       3   9.273 ± 1.490  ops/ms
ClientGrpc.getUser                         thrpt       3   8.620 ± 3.974  ops/ms
ClientGrpc.listUser                        thrpt       3   6.623 ± 1.579  ops/ms
ClientGrpc.createUser                       avgt       3   3.668 ± 0.597   ms/op
ClientGrpc.existUser                        avgt       3   3.476 ± 0.734   ms/op
ClientGrpc.getUser                          avgt       3   3.743 ± 1.261   ms/op
ClientGrpc.listUser                         avgt       3   4.782 ± 1.166   ms/op
ClientGrpc.createUser                     sample  259466   3.698 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.930           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.249           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.187           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.808           ms/op
ClientGrpc.existUser                      sample  274553   3.498 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.886           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.039           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.132           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.055           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  259430   3.698 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.911           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.710           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.257           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.037           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.132           ms/op
ClientGrpc.listUser                       sample  199260   4.823 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.798           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.111           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.651           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.195           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.400           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.184           ms/op
