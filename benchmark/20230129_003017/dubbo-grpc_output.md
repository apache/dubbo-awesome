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
# Warmup Iteration   1: 2.027 ops/ms
# Warmup Iteration   2: 4.909 ops/ms
# Warmup Iteration   3: 6.667 ops/ms
Iteration   1: 6.754 ops/ms
Iteration   2: 6.802 ops/ms
Iteration   3: 6.702 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.753 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (6.702, 6.753, 6.802), stdev = 0.050
  CI (99.9%): [5.840, 7.666] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.499 ops/ms
# Warmup Iteration   2: 6.595 ops/ms
# Warmup Iteration   3: 6.967 ops/ms
Iteration   1: 6.857 ops/ms
Iteration   2: 6.836 ops/ms
Iteration   3: 7.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.001 ±(99.9%) 4.897 ops/ms [Average]
  (min, avg, max) = (6.836, 7.001, 7.311), stdev = 0.268
  CI (99.9%): [2.104, 11.899] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.011 ops/ms
# Warmup Iteration   2: 6.327 ops/ms
# Warmup Iteration   3: 6.665 ops/ms
Iteration   1: 6.613 ops/ms
Iteration   2: 6.809 ops/ms
Iteration   3: 6.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.686 ±(99.9%) 1.946 ops/ms [Average]
  (min, avg, max) = (6.613, 6.686, 6.809), stdev = 0.107
  CI (99.9%): [4.740, 8.633] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.626 ops/ms
# Warmup Iteration   2: 4.882 ops/ms
# Warmup Iteration   3: 5.303 ops/ms
Iteration   1: 5.570 ops/ms
Iteration   2: 5.548 ops/ms
Iteration   3: 5.629 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.583 ±(99.9%) 0.763 ops/ms [Average]
  (min, avg, max) = (5.548, 5.583, 5.629), stdev = 0.042
  CI (99.9%): [4.820, 6.346] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.089 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.851 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 4.638 ±(99.9%) 0.012 ms/op
Iteration   1: 4.530 ±(99.9%) 0.003 ms/op
Iteration   2: 4.691 ±(99.9%) 0.003 ms/op
Iteration   3: 4.657 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.626 ±(99.9%) 1.549 ms/op [Average]
  (min, avg, max) = (4.530, 4.626, 4.691), stdev = 0.085
  CI (99.9%): [3.076, 6.175] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.486 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.549 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.366 ±(99.9%) 0.005 ms/op
Iteration   1: 4.238 ±(99.9%) 0.009 ms/op
Iteration   2: 4.407 ±(99.9%) 0.003 ms/op
Iteration   3: 4.520 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.388 ±(99.9%) 2.593 ms/op [Average]
  (min, avg, max) = (4.238, 4.388, 4.520), stdev = 0.142
  CI (99.9%): [1.795, 6.981] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.891 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 5.023 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.679 ±(99.9%) 0.013 ms/op
Iteration   1: 4.749 ±(99.9%) 0.003 ms/op
Iteration   2: 4.663 ±(99.9%) 0.004 ms/op
Iteration   3: 4.747 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.719 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (4.663, 4.719, 4.749), stdev = 0.049
  CI (99.9%): [3.825, 5.613] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 8.131 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 6.371 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 6.183 ±(99.9%) 0.020 ms/op
Iteration   1: 5.751 ±(99.9%) 0.014 ms/op
Iteration   2: 5.731 ±(99.9%) 0.015 ms/op
Iteration   3: 5.669 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.717 ±(99.9%) 0.783 ms/op [Average]
  (min, avg, max) = (5.669, 5.717, 5.751), stdev = 0.043
  CI (99.9%): [4.934, 6.500] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.846 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.809 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.659 ±(99.9%) 0.015 ms/op
Iteration   1: 4.819 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   4.735 ms/op
                 createUser·p0.90:   6.103 ms/op
                 createUser·p0.95:   6.562 ms/op
                 createUser·p0.99:   8.167 ms/op
                 createUser·p0.999:  13.860 ms/op
                 createUser·p0.9999: 21.270 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   2: 4.593 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   5.882 ms/op
                 createUser·p0.95:   6.308 ms/op
                 createUser·p0.99:   7.561 ms/op
                 createUser·p0.999:  10.852 ms/op
                 createUser·p0.9999: 24.485 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 4.848 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   4.768 ms/op
                 createUser·p0.90:   6.046 ms/op
                 createUser·p0.95:   6.382 ms/op
                 createUser·p0.99:   7.586 ms/op
                 createUser·p0.999:  15.386 ms/op
                 createUser·p0.9999: 30.179 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 201956
  mean =      4.751 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3352 
    [ 2.500,  5.000) = 123468 
    [ 5.000,  7.500) = 72528 
    [ 7.500, 10.000) = 2072 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      4.661 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.414 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     29.347 ms/op
     p(99.9990) =     30.472 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.793 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.737 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.469 ±(99.9%) 0.013 ms/op
Iteration   1: 4.610 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.870 ms/op
                 existUser·p0.50:   4.538 ms/op
                 existUser·p0.90:   5.800 ms/op
                 existUser·p0.95:   6.169 ms/op
                 existUser·p0.99:   7.455 ms/op
                 existUser·p0.999:  12.263 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 4.486 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   4.415 ms/op
                 existUser·p0.90:   5.743 ms/op
                 existUser·p0.95:   6.144 ms/op
                 existUser·p0.99:   7.537 ms/op
                 existUser·p0.999:  11.305 ms/op
                 existUser·p0.9999: 21.382 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   3: 4.415 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   4.366 ms/op
                 existUser·p0.90:   5.685 ms/op
                 existUser·p0.95:   6.087 ms/op
                 existUser·p0.99:   7.778 ms/op
                 existUser·p0.999:  15.776 ms/op
                 existUser·p0.9999: 22.560 ms/op
                 existUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 213269
  mean =      4.502 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8023 
    [ 2.500,  5.000) = 143427 
    [ 5.000,  7.500) = 59573 
    [ 7.500, 10.000) = 1675 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.743 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     12.738 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     24.596 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.094 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.951 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.716 ±(99.9%) 0.015 ms/op
Iteration   1: 4.815 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   6.128 ms/op
                 getUser·p0.95:   6.545 ms/op
                 getUser·p0.99:   8.094 ms/op
                 getUser·p0.999:  11.668 ms/op
                 getUser·p0.9999: 16.650 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   2: 4.991 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   4.899 ms/op
                 getUser·p0.90:   6.242 ms/op
                 getUser·p0.95:   6.709 ms/op
                 getUser·p0.99:   8.684 ms/op
                 getUser·p0.999:  11.501 ms/op
                 getUser·p0.9999: 19.058 ms/op
                 getUser·p1.00:   20.447 ms/op

Iteration   3: 4.803 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   4.719 ms/op
                 getUser·p0.90:   6.038 ms/op
                 getUser·p0.95:   6.455 ms/op
                 getUser·p0.99:   8.409 ms/op
                 getUser·p0.999:  12.211 ms/op
                 getUser·p0.9999: 37.639 ms/op
                 getUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 197191
  mean =      4.868 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2509 
    [ 2.500,  5.000) = 113744 
    [ 5.000,  7.500) = 77068 
    [ 7.500, 10.000) = 3279 
    [10.000, 12.500) = 456 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      4.768 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      6.570 ms/op
     p(99.0000) =      8.438 ms/op
     p(99.9000) =     11.695 ms/op
     p(99.9900) =     36.635 ms/op
     p(99.9990) =     37.949 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.406 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 6.487 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 5.758 ±(99.9%) 0.021 ms/op
Iteration   1: 5.832 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   5.554 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  16.612 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 5.767 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.219 ms/op
                 listUser·p0.50:   5.538 ms/op
                 listUser·p0.90:   7.373 ms/op
                 listUser·p0.95:   8.282 ms/op
                 listUser·p0.99:   10.519 ms/op
                 listUser·p0.999:  16.540 ms/op
                 listUser·p0.9999: 26.751 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   3: 5.973 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   5.677 ms/op
                 listUser·p0.90:   7.832 ms/op
                 listUser·p0.95:   8.700 ms/op
                 listUser·p0.99:   10.994 ms/op
                 listUser·p0.999:  22.479 ms/op
                 listUser·p0.9999: 24.904 ms/op
                 listUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 163916
  mean =      5.856 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 42554 
    [ 5.000,  7.500) = 102902 
    [ 7.500, 10.000) = 15759 
    [10.000, 12.500) = 2082 
    [12.500, 15.000) = 253 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.196 ms/op
     p(50.0000) =      5.587 ms/op
     p(90.0000) =      7.660 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     10.712 ms/op
     p(99.9000) =     17.651 ms/op
     p(99.9900) =     25.116 ms/op
     p(99.9990) =     27.444 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.753 ± 0.913  ops/ms
ClientGrpc.existUser                       thrpt       3   7.001 ± 4.897  ops/ms
ClientGrpc.getUser                         thrpt       3   6.686 ± 1.946  ops/ms
ClientGrpc.listUser                        thrpt       3   5.583 ± 0.763  ops/ms
ClientGrpc.createUser                       avgt       3   4.626 ± 1.549   ms/op
ClientGrpc.existUser                        avgt       3   4.388 ± 2.593   ms/op
ClientGrpc.getUser                          avgt       3   4.719 ± 0.894   ms/op
ClientGrpc.listUser                         avgt       3   5.717 ± 0.783   ms/op
ClientGrpc.createUser                     sample  201956   4.751 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.899           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.021           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.414           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.807           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.812           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.347           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.671           ms/op
ClientGrpc.existUser                      sample  213269   4.502 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.825           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.743           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.136           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.578           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.738           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.987           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.740           ms/op
ClientGrpc.getUser                        sample  197191   4.868 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.106           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.768           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.136           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.570           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.438           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.695           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          36.635           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          38.076           ms/op
ClientGrpc.listUser                       sample  163916   5.856 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.196           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.660           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.503           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.712           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.651           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.116           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.591           ms/op
