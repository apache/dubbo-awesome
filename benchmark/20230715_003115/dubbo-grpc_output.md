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
# Warmup Iteration   1: 2.976 ops/ms
# Warmup Iteration   2: 7.080 ops/ms
# Warmup Iteration   3: 8.165 ops/ms
Iteration   1: 8.822 ops/ms
Iteration   2: 8.854 ops/ms
Iteration   3: 8.946 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.874 ±(99.9%) 1.176 ops/ms [Average]
  (min, avg, max) = (8.822, 8.874, 8.946), stdev = 0.064
  CI (99.9%): [7.698, 10.050] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.248 ops/ms
# Warmup Iteration   2: 8.927 ops/ms
# Warmup Iteration   3: 9.551 ops/ms
Iteration   1: 9.301 ops/ms
Iteration   2: 9.238 ops/ms
Iteration   3: 9.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.304 ±(99.9%) 1.214 ops/ms [Average]
  (min, avg, max) = (9.238, 9.304, 9.371), stdev = 0.067
  CI (99.9%): [8.090, 10.517] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.372 ops/ms
# Warmup Iteration   2: 8.610 ops/ms
# Warmup Iteration   3: 9.051 ops/ms
Iteration   1: 9.026 ops/ms
Iteration   2: 9.088 ops/ms
Iteration   3: 8.815 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.976 ±(99.9%) 2.619 ops/ms [Average]
  (min, avg, max) = (8.815, 8.976, 9.088), stdev = 0.144
  CI (99.9%): [6.357, 11.595] (assumes normal distribution)


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
# Warmup Iteration   1: 4.215 ops/ms
# Warmup Iteration   2: 6.135 ops/ms
# Warmup Iteration   3: 6.728 ops/ms
Iteration   1: 6.515 ops/ms
Iteration   2: 6.350 ops/ms
Iteration   3: 6.779 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.548 ±(99.9%) 3.944 ops/ms [Average]
  (min, avg, max) = (6.350, 6.548, 6.779), stdev = 0.216
  CI (99.9%): [2.604, 10.492] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.396 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.641 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.664 ±(99.9%) 0.023 ms/op
Iteration   1: 3.628 ±(99.9%) 0.001 ms/op
Iteration   2: 3.761 ±(99.9%) 0.002 ms/op
Iteration   3: 3.542 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.644 ±(99.9%) 2.012 ms/op [Average]
  (min, avg, max) = (3.542, 3.644, 3.761), stdev = 0.110
  CI (99.9%): [1.632, 5.656] (assumes normal distribution)


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
# Warmup Iteration   1: 4.918 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.667 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.003 ms/op
Iteration   1: 3.395 ±(99.9%) 0.003 ms/op
Iteration   2: 3.403 ±(99.9%) 0.002 ms/op
Iteration   3: 3.339 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.379 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (3.339, 3.379, 3.403), stdev = 0.035
  CI (99.9%): [2.745, 4.014] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 5.074 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.659 ±(99.9%) 0.002 ms/op
Iteration   1: 3.716 ±(99.9%) 0.003 ms/op
Iteration   2: 3.726 ±(99.9%) 0.001 ms/op
Iteration   3: 3.599 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.680 ±(99.9%) 1.288 ms/op [Average]
  (min, avg, max) = (3.599, 3.680, 3.726), stdev = 0.071
  CI (99.9%): [2.392, 4.968] (assumes normal distribution)


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
# Warmup Iteration   1: 6.893 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.797 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.779 ±(99.9%) 0.016 ms/op
Iteration   1: 4.622 ±(99.9%) 0.016 ms/op
Iteration   2: 4.630 ±(99.9%) 0.013 ms/op
Iteration   3: 4.597 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.616 ±(99.9%) 0.310 ms/op [Average]
  (min, avg, max) = (4.597, 4.616, 4.630), stdev = 0.017
  CI (99.9%): [4.306, 4.927] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.221 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.011 ms/op
Iteration   1: 3.681 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.728 ms/op
                 createUser·p0.50:   3.572 ms/op
                 createUser·p0.90:   4.637 ms/op
                 createUser·p0.95:   5.046 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  12.618 ms/op
                 createUser·p0.9999: 14.957 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   2: 3.686 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.568 ms/op
                 createUser·p0.50:   3.527 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.153 ms/op
                 createUser·p0.99:   7.014 ms/op
                 createUser·p0.999:  12.996 ms/op
                 createUser·p0.9999: 15.668 ms/op
                 createUser·p1.00:   15.729 ms/op

Iteration   3: 3.680 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.995 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  11.815 ms/op
                 createUser·p0.9999: 18.219 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260642
  mean =      3.682 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 78 
    [ 1.250,  2.500) = 6027 
    [ 2.500,  3.750) = 152214 
    [ 3.750,  5.000) = 88357 
    [ 5.000,  6.250) = 10861 
    [ 6.250,  7.500) = 1742 
    [ 7.500,  8.750) = 636 
    [ 8.750, 10.000) = 225 
    [10.000, 11.250) = 109 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 43 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.559 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.046 ms/op
     p(99.0000) =      6.452 ms/op
     p(99.9000) =     12.660 ms/op
     p(99.9900) =     17.826 ms/op
     p(99.9990) =     18.920 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.765 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.009 ms/op
Iteration   1: 3.354 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   4.170 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 16.856 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 3.416 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   5.803 ms/op
                 existUser·p0.999:  11.174 ms/op
                 existUser·p0.9999: 25.428 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  11.764 ms/op
                 existUser·p0.9999: 17.433 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 284756
  mean =      3.371 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17630 
    [ 2.500,  5.000) = 259485 
    [ 5.000,  7.500) = 6753 
    [ 7.500, 10.000) = 566 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.277 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.857 ms/op
     p(99.9000) =     10.621 ms/op
     p(99.9900) =     24.610 ms/op
     p(99.9990) =     25.695 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 5.502 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.694 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.010 ms/op
Iteration   1: 3.589 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.494 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.020 ms/op
                 getUser·p0.999:  10.402 ms/op
                 getUser·p0.9999: 17.471 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   2: 3.633 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.522 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   5.931 ms/op
                 getUser·p0.999:  8.667 ms/op
                 getUser·p0.9999: 22.229 ms/op
                 getUser·p1.00:   23.396 ms/op

Iteration   3: 3.567 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   3.486 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  11.856 ms/op
                 getUser·p0.9999: 19.399 ms/op
                 getUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 266940
  mean =      3.596 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9522 
    [ 2.500,  5.000) = 247103 
    [ 5.000,  7.500) = 9466 
    [ 7.500, 10.000) = 586 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     22.936 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


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
# Warmup Iteration   1: 6.523 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.173 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.006 ±(99.9%) 0.018 ms/op
Iteration   1: 4.909 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   6.406 ms/op
                 listUser·p0.95:   7.184 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  15.560 ms/op
                 listUser·p0.9999: 23.001 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 4.719 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.832 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  19.658 ms/op
                 listUser·p0.9999: 37.960 ms/op
                 listUser·p1.00:   38.928 ms/op

Iteration   3: 4.622 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.286 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   6.098 ms/op
                 listUser·p0.95:   6.922 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  17.262 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202218
  mean =      4.747 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 698 
    [ 2.500,  5.000) = 140725 
    [ 5.000,  7.500) = 54160 
    [ 7.500, 10.000) = 5547 
    [10.000, 12.500) = 614 
    [12.500, 15.000) = 152 
    [15.000, 17.500) = 130 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      6.169 ms/op
     p(95.0000) =      6.996 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     17.327 ms/op
     p(99.9900) =     36.372 ms/op
     p(99.9990) =     38.924 ms/op
     p(99.9999) =     38.928 ms/op
    p(100.0000) =     38.928 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.874 ± 1.176  ops/ms
ClientGrpc.existUser                       thrpt       3   9.304 ± 1.214  ops/ms
ClientGrpc.getUser                         thrpt       3   8.976 ± 2.619  ops/ms
ClientGrpc.listUser                        thrpt       3   6.548 ± 3.944  ops/ms
ClientGrpc.createUser                       avgt       3   3.644 ± 2.012   ms/op
ClientGrpc.existUser                        avgt       3   3.379 ± 0.635   ms/op
ClientGrpc.getUser                          avgt       3   3.680 ± 1.288   ms/op
ClientGrpc.listUser                         avgt       3   4.616 ± 0.310   ms/op
ClientGrpc.createUser                     sample  260642   3.682 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.568           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.559           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.452           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.660           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.826           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.038           ms/op
ClientGrpc.existUser                      sample  284756   3.371 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.721           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.277           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.857           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.621           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.610           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.313           ms/op
ClientGrpc.getUser                        sample  266940   3.596 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.836           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.980           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.945           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.987           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.396           ms/op
ClientGrpc.listUser                       sample  202218   4.747 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.196           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.530           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.169           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.996           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.011           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.327           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          36.372           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          38.928           ms/op
