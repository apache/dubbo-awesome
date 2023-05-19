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
# Warmup Iteration   1: 3.219 ops/ms
# Warmup Iteration   2: 6.789 ops/ms
# Warmup Iteration   3: 8.030 ops/ms
Iteration   1: 8.489 ops/ms
Iteration   2: 8.653 ops/ms
Iteration   3: 8.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.542 ±(99.9%) 1.760 ops/ms [Average]
  (min, avg, max) = (8.484, 8.542, 8.653), stdev = 0.096
  CI (99.9%): [6.782, 10.302] (assumes normal distribution)


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
# Warmup Iteration   1: 5.740 ops/ms
# Warmup Iteration   2: 8.394 ops/ms
# Warmup Iteration   3: 8.940 ops/ms
Iteration   1: 9.515 ops/ms
Iteration   2: 9.035 ops/ms
Iteration   3: 9.165 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.239 ±(99.9%) 4.529 ops/ms [Average]
  (min, avg, max) = (9.035, 9.239, 9.515), stdev = 0.248
  CI (99.9%): [4.710, 13.768] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.490 ops/ms
# Warmup Iteration   2: 7.925 ops/ms
# Warmup Iteration   3: 8.569 ops/ms
Iteration   1: 8.612 ops/ms
Iteration   2: 8.718 ops/ms
Iteration   3: 8.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.694 ±(99.9%) 1.330 ops/ms [Average]
  (min, avg, max) = (8.612, 8.694, 8.751), stdev = 0.073
  CI (99.9%): [7.364, 10.024] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.105 ops/ms
# Warmup Iteration   2: 6.234 ops/ms
# Warmup Iteration   3: 6.282 ops/ms
Iteration   1: 6.625 ops/ms
Iteration   2: 6.416 ops/ms
Iteration   3: 6.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.548 ±(99.9%) 2.094 ops/ms [Average]
  (min, avg, max) = (6.416, 6.548, 6.625), stdev = 0.115
  CI (99.9%): [4.454, 8.641] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.749 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.042 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.004 ms/op
Iteration   1: 3.704 ±(99.9%) 0.004 ms/op
Iteration   2: 3.623 ±(99.9%) 0.004 ms/op
Iteration   3: 3.663 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.663 ±(99.9%) 0.738 ms/op [Average]
  (min, avg, max) = (3.623, 3.663, 3.704), stdev = 0.040
  CI (99.9%): [2.925, 4.402] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.913 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.649 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.004 ms/op
Iteration   1: 3.521 ±(99.9%) 0.004 ms/op
Iteration   2: 3.570 ±(99.9%) 0.003 ms/op
Iteration   3: 3.465 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.519 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (3.465, 3.519, 3.570), stdev = 0.053
  CI (99.9%): [2.557, 4.480] (assumes normal distribution)


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
# Warmup Iteration   1: 5.131 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.751 ±(99.9%) 0.011 ms/op
Iteration   1: 3.715 ±(99.9%) 0.007 ms/op
Iteration   2: 3.776 ±(99.9%) 0.005 ms/op
Iteration   3: 3.654 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.715 ±(99.9%) 1.112 ms/op [Average]
  (min, avg, max) = (3.654, 3.715, 3.776), stdev = 0.061
  CI (99.9%): [2.603, 4.826] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.750 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.190 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.926 ±(99.9%) 0.016 ms/op
Iteration   1: 4.795 ±(99.9%) 0.015 ms/op
Iteration   2: 4.836 ±(99.9%) 0.015 ms/op
Iteration   3: 4.743 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.791 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (4.743, 4.791, 4.836), stdev = 0.046
  CI (99.9%): [3.943, 5.639] (assumes normal distribution)


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
# Warmup Iteration   1: 5.397 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.010 ms/op
Iteration   1: 3.652 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.489 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.930 ms/op
                 createUser·p0.999:  11.551 ms/op
                 createUser·p0.9999: 14.172 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   2: 3.742 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.808 ms/op
                 createUser·p0.999:  11.633 ms/op
                 createUser·p0.9999: 27.638 ms/op
                 createUser·p1.00:   27.984 ms/op

Iteration   3: 3.584 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   3.551 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.898 ms/op
                 createUser·p0.999:  8.827 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262288
  mean =      3.658 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10749 
    [ 2.500,  5.000) = 242347 
    [ 5.000,  7.500) = 7631 
    [ 7.500, 10.000) = 1111 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     11.469 ms/op
     p(99.9900) =     26.404 ms/op
     p(99.9990) =     27.878 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.591 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.009 ms/op
Iteration   1: 3.581 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   3.506 ms/op
                 existUser·p0.90:   4.309 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   6.439 ms/op
                 existUser·p0.999:  10.387 ms/op
                 existUser·p0.9999: 14.828 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   2: 3.595 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.353 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   6.270 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 20.549 ms/op
                 existUser·p1.00:   21.594 ms/op

Iteration   3: 3.494 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  8.782 ms/op
                 existUser·p0.9999: 29.120 ms/op
                 existUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269947
  mean =      3.556 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10212 
    [ 2.500,  5.000) = 251696 
    [ 5.000,  7.500) = 6775 
    [ 7.500, 10.000) = 1029 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.478 ms/op
     p(90.0000) =      4.252 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.160 ms/op
     p(99.9000) =      9.766 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     29.347 ms/op
     p(99.9999) =     29.458 ms/op
    p(100.0000) =     29.458 ms/op


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
# Warmup Iteration   1: 5.070 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.948 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.010 ms/op
Iteration   1: 3.771 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.063 ms/op
                 getUser·p0.99:   7.285 ms/op
                 getUser·p0.999:  12.309 ms/op
                 getUser·p0.9999: 17.170 ms/op
                 getUser·p1.00:   17.433 ms/op

Iteration   2: 3.685 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.448 ms/op
                 getUser·p0.95:   4.850 ms/op
                 getUser·p0.99:   5.988 ms/op
                 getUser·p0.999:  8.733 ms/op
                 getUser·p0.9999: 17.640 ms/op
                 getUser·p1.00:   17.990 ms/op

Iteration   3: 3.767 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.757 ms/op
                 getUser·p0.50:   3.658 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  11.487 ms/op
                 getUser·p0.9999: 20.693 ms/op
                 getUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 256619
  mean =      3.740 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9285 
    [ 2.500,  5.000) = 235038 
    [ 5.000,  7.500) = 10617 
    [ 7.500, 10.000) = 1324 
    [10.000, 12.500) = 178 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     10.682 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     20.855 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 6.927 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 5.287 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.158 ±(99.9%) 0.020 ms/op
Iteration   1: 4.992 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.717 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   10.461 ms/op
                 listUser·p0.999:  17.038 ms/op
                 listUser·p0.9999: 18.337 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   2: 4.796 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.407 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   7.135 ms/op
                 listUser·p0.99:   9.175 ms/op
                 listUser·p0.999:  16.107 ms/op
                 listUser·p0.9999: 22.523 ms/op
                 listUser·p1.00:   26.444 ms/op

Iteration   3: 4.827 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   0.535 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   6.668 ms/op
                 listUser·p0.95:   7.586 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  21.353 ms/op
                 listUser·p0.9999: 29.289 ms/op
                 listUser·p1.00:   30.638 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 197052
  mean =      4.870 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 739 
    [ 2.500,  5.000) = 136280 
    [ 5.000,  7.500) = 50323 
    [ 7.500, 10.000) = 8071 
    [10.000, 12.500) = 1061 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.535 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.537 ms/op
     p(95.0000) =      7.482 ms/op
     p(99.0000) =      9.683 ms/op
     p(99.9000) =     18.088 ms/op
     p(99.9900) =     28.606 ms/op
     p(99.9990) =     30.543 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.542 ± 1.760  ops/ms
ClientGrpc.existUser                       thrpt       3   9.239 ± 4.529  ops/ms
ClientGrpc.getUser                         thrpt       3   8.694 ± 1.330  ops/ms
ClientGrpc.listUser                        thrpt       3   6.548 ± 2.094  ops/ms
ClientGrpc.createUser                       avgt       3   3.663 ± 0.738   ms/op
ClientGrpc.existUser                        avgt       3   3.519 ± 0.962   ms/op
ClientGrpc.getUser                          avgt       3   3.715 ± 1.112   ms/op
ClientGrpc.listUser                         avgt       3   4.791 ± 0.848   ms/op
ClientGrpc.createUser                     sample  262288   3.658 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.778           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.596           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.463           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.469           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.404           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.984           ms/op
ClientGrpc.existUser                      sample  269947   3.556 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.915           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.160           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.766           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.001           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.458           ms/op
ClientGrpc.getUser                        sample  256619   3.740 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.757           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.973           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.799           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.682           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.185           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.939           ms/op
ClientGrpc.listUser                       sample  197052   4.870 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.535           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.563           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.482           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.683           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.088           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.606           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.638           ms/op
