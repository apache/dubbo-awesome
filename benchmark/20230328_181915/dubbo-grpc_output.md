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
# Warmup Iteration   1: 3.180 ops/ms
# Warmup Iteration   2: 6.999 ops/ms
# Warmup Iteration   3: 7.966 ops/ms
Iteration   1: 8.521 ops/ms
Iteration   2: 8.690 ops/ms
Iteration   3: 8.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.537 ±(99.9%) 2.648 ops/ms [Average]
  (min, avg, max) = (8.401, 8.537, 8.690), stdev = 0.145
  CI (99.9%): [5.890, 11.185] (assumes normal distribution)


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
# Warmup Iteration   1: 5.538 ops/ms
# Warmup Iteration   2: 8.283 ops/ms
# Warmup Iteration   3: 9.269 ops/ms
Iteration   1: 9.119 ops/ms
Iteration   2: 8.995 ops/ms
Iteration   3: 9.134 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.082 ±(99.9%) 1.392 ops/ms [Average]
  (min, avg, max) = (8.995, 9.082, 9.134), stdev = 0.076
  CI (99.9%): [7.691, 10.474] (assumes normal distribution)


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
# Warmup Iteration   1: 5.380 ops/ms
# Warmup Iteration   2: 8.352 ops/ms
# Warmup Iteration   3: 8.714 ops/ms
Iteration   1: 8.700 ops/ms
Iteration   2: 8.747 ops/ms
Iteration   3: 8.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.709 ±(99.9%) 0.626 ops/ms [Average]
  (min, avg, max) = (8.681, 8.709, 8.747), stdev = 0.034
  CI (99.9%): [8.084, 9.335] (assumes normal distribution)


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
# Warmup Iteration   1: 4.338 ops/ms
# Warmup Iteration   2: 6.310 ops/ms
# Warmup Iteration   3: 6.774 ops/ms
Iteration   1: 6.591 ops/ms
Iteration   2: 6.701 ops/ms
Iteration   3: 6.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.645 ±(99.9%) 1.005 ops/ms [Average]
  (min, avg, max) = (6.591, 6.645, 6.701), stdev = 0.055
  CI (99.9%): [5.640, 7.650] (assumes normal distribution)


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
# Warmup Iteration   1: 5.012 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.006 ms/op
Iteration   1: 3.751 ±(99.9%) 0.002 ms/op
Iteration   2: 3.724 ±(99.9%) 0.003 ms/op
Iteration   3: 3.688 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.721 ±(99.9%) 0.578 ms/op [Average]
  (min, avg, max) = (3.688, 3.721, 3.751), stdev = 0.032
  CI (99.9%): [3.144, 4.299] (assumes normal distribution)


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
# Warmup Iteration   1: 4.698 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.004 ms/op
Iteration   1: 3.529 ±(99.9%) 0.004 ms/op
Iteration   2: 3.436 ±(99.9%) 0.004 ms/op
Iteration   3: 3.577 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.514 ±(99.9%) 1.304 ms/op [Average]
  (min, avg, max) = (3.436, 3.514, 3.577), stdev = 0.071
  CI (99.9%): [2.211, 4.818] (assumes normal distribution)


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
# Warmup Iteration   1: 5.193 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.003 ms/op
Iteration   1: 3.648 ±(99.9%) 0.005 ms/op
Iteration   2: 3.705 ±(99.9%) 0.005 ms/op
Iteration   3: 3.721 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.692 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (3.648, 3.692, 3.721), stdev = 0.038
  CI (99.9%): [2.994, 4.389] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.834 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.224 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.883 ±(99.9%) 0.012 ms/op
Iteration   1: 4.801 ±(99.9%) 0.012 ms/op
Iteration   2: 4.740 ±(99.9%) 0.009 ms/op
Iteration   3: 4.826 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.789 ±(99.9%) 0.813 ms/op [Average]
  (min, avg, max) = (4.740, 4.789, 4.826), stdev = 0.045
  CI (99.9%): [3.976, 5.602] (assumes normal distribution)


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
# Warmup Iteration   1: 5.213 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.859 ±(99.9%) 0.010 ms/op
Iteration   1: 3.814 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.736 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  12.159 ms/op
                 createUser·p0.9999: 14.893 ms/op
                 createUser·p1.00:   15.204 ms/op

Iteration   2: 3.754 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.874 ms/op
                 createUser·p0.50:   3.654 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  12.206 ms/op
                 createUser·p0.9999: 18.202 ms/op
                 createUser·p1.00:   18.416 ms/op

Iteration   3: 3.647 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.584 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.652 ms/op
                 createUser·p0.999:  12.829 ms/op
                 createUser·p0.9999: 23.535 ms/op
                 createUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 256961
  mean =      3.737 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5919 
    [ 2.500,  5.000) = 240679 
    [ 5.000,  7.500) = 9174 
    [ 7.500, 10.000) = 774 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     12.256 ms/op
     p(99.9900) =     22.080 ms/op
     p(99.9990) =     23.799 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.172 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.010 ms/op
Iteration   1: 3.526 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.790 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  10.846 ms/op
                 existUser·p0.9999: 26.209 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   2: 3.463 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   3.416 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   5.693 ms/op
                 existUser·p0.999:  9.298 ms/op
                 existUser·p0.9999: 19.694 ms/op
                 existUser·p1.00:   20.152 ms/op

Iteration   3: 3.489 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.907 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  9.077 ms/op
                 existUser·p0.9999: 21.987 ms/op
                 existUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274945
  mean =      3.493 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13857 
    [ 2.500,  5.000) = 254313 
    [ 5.000,  7.500) = 5777 
    [ 7.500, 10.000) = 681 
    [10.000, 12.500) = 189 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.790 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     10.273 ms/op
     p(99.9900) =     23.102 ms/op
     p(99.9990) =     26.624 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 5.453 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.008 ms/op
Iteration   1: 3.660 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.788 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  13.877 ms/op
                 getUser·p0.9999: 22.282 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   2: 3.647 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.075 ms/op
                 getUser·p0.50:   3.580 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.612 ms/op
                 getUser·p0.99:   5.693 ms/op
                 getUser·p0.999:  10.404 ms/op
                 getUser·p0.9999: 15.876 ms/op
                 getUser·p1.00:   16.499 ms/op

Iteration   3: 3.701 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   3.625 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   5.956 ms/op
                 getUser·p0.999:  9.955 ms/op
                 getUser·p0.9999: 20.361 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261694
  mean =      3.669 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6809 
    [ 2.500,  5.000) = 246714 
    [ 5.000,  7.500) = 7396 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     10.458 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     22.426 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


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
# Warmup Iteration   1: 6.696 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.978 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.578 ±(99.9%) 0.013 ms/op
Iteration   1: 4.757 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   6.029 ms/op
                 listUser·p0.95:   6.922 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  15.909 ms/op
                 listUser·p0.9999: 17.105 ms/op
                 listUser·p1.00:   17.596 ms/op

Iteration   2: 4.796 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.421 ms/op
                 listUser·p0.999:  16.907 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 4.731 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.346 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.784 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.249 ms/op
                 listUser·p0.999:  19.825 ms/op
                 listUser·p0.9999: 25.895 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 201450
  mean =      4.761 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 261 
    [ 2.500,  5.000) = 152531 
    [ 5.000,  7.500) = 43604 
    [ 7.500, 10.000) = 4287 
    [10.000, 12.500) = 372 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.923 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     16.451 ms/op
     p(99.9900) =     24.440 ms/op
     p(99.9990) =     26.115 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.537 ± 2.648  ops/ms
ClientGrpc.existUser                       thrpt       3   9.082 ± 1.392  ops/ms
ClientGrpc.getUser                         thrpt       3   8.709 ± 0.626  ops/ms
ClientGrpc.listUser                        thrpt       3   6.645 ± 1.005  ops/ms
ClientGrpc.createUser                       avgt       3   3.721 ± 0.578   ms/op
ClientGrpc.existUser                        avgt       3   3.514 ± 1.304   ms/op
ClientGrpc.getUser                          avgt       3   3.692 ± 0.698   ms/op
ClientGrpc.listUser                         avgt       3   4.789 ± 0.813   ms/op
ClientGrpc.createUser                     sample  256961   3.737 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.686           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.874           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.136           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.256           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.080           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.953           ms/op
ClientGrpc.existUser                      sample  274945   3.493 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.790           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.445           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.800           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.273           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.102           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.739           ms/op
ClientGrpc.getUser                        sample  261694   3.669 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.788           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.890           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.458           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.856           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.479           ms/op
ClientGrpc.listUser                       sample  201450   4.761 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.346           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.923           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.451           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.440           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.313           ms/op
