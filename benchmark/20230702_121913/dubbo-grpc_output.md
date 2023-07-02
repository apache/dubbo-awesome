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
# Warmup Iteration   1: 2.726 ops/ms
# Warmup Iteration   2: 6.857 ops/ms
# Warmup Iteration   3: 8.663 ops/ms
Iteration   1: 8.752 ops/ms
Iteration   2: 9.043 ops/ms
Iteration   3: 9.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.972 ±(99.9%) 3.555 ops/ms [Average]
  (min, avg, max) = (8.752, 8.972, 9.121), stdev = 0.195
  CI (99.9%): [5.417, 12.528] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.594 ops/ms
# Warmup Iteration   2: 9.018 ops/ms
# Warmup Iteration   3: 9.706 ops/ms
Iteration   1: 9.689 ops/ms
Iteration   2: 9.893 ops/ms
Iteration   3: 9.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.798 ±(99.9%) 1.870 ops/ms [Average]
  (min, avg, max) = (9.689, 9.798, 9.893), stdev = 0.102
  CI (99.9%): [7.928, 11.667] (assumes normal distribution)


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
# Warmup Iteration   1: 5.460 ops/ms
# Warmup Iteration   2: 8.539 ops/ms
# Warmup Iteration   3: 8.834 ops/ms
Iteration   1: 9.100 ops/ms
Iteration   2: 9.298 ops/ms
Iteration   3: 9.177 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.191 ±(99.9%) 1.821 ops/ms [Average]
  (min, avg, max) = (9.100, 9.191, 9.298), stdev = 0.100
  CI (99.9%): [7.370, 11.012] (assumes normal distribution)


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
# Warmup Iteration   1: 4.174 ops/ms
# Warmup Iteration   2: 6.479 ops/ms
# Warmup Iteration   3: 6.922 ops/ms
Iteration   1: 6.860 ops/ms
Iteration   2: 6.820 ops/ms
Iteration   3: 6.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.819 ±(99.9%) 0.760 ops/ms [Average]
  (min, avg, max) = (6.777, 6.819, 6.860), stdev = 0.042
  CI (99.9%): [6.059, 7.579] (assumes normal distribution)


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.012 ms/op
Iteration   1: 3.451 ±(99.9%) 0.002 ms/op
Iteration   2: 3.507 ±(99.9%) 0.001 ms/op
Iteration   3: 3.505 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.488 ±(99.9%) 0.574 ms/op [Average]
  (min, avg, max) = (3.451, 3.488, 3.507), stdev = 0.031
  CI (99.9%): [2.914, 4.062] (assumes normal distribution)


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
# Warmup Iteration   1: 4.850 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.003 ms/op
Iteration   1: 3.356 ±(99.9%) 0.001 ms/op
Iteration   2: 3.384 ±(99.9%) 0.002 ms/op
Iteration   3: 3.298 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.346 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (3.298, 3.346, 3.384), stdev = 0.044
  CI (99.9%): [2.543, 4.149] (assumes normal distribution)


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
# Warmup Iteration   1: 5.228 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.002 ms/op
Iteration   1: 3.610 ±(99.9%) 0.002 ms/op
Iteration   2: 3.680 ±(99.9%) 0.002 ms/op
Iteration   3: 3.623 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.638 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (3.610, 3.638, 3.680), stdev = 0.038
  CI (99.9%): [2.953, 4.323] (assumes normal distribution)


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
# Warmup Iteration   1: 7.101 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.993 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.700 ±(99.9%) 0.012 ms/op
Iteration   1: 4.657 ±(99.9%) 0.012 ms/op
Iteration   2: 4.764 ±(99.9%) 0.012 ms/op
Iteration   3: 4.663 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.695 ±(99.9%) 1.096 ms/op [Average]
  (min, avg, max) = (4.657, 4.695, 4.764), stdev = 0.060
  CI (99.9%): [3.598, 5.791] (assumes normal distribution)


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
# Warmup Iteration   1: 4.850 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.844 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.010 ms/op
Iteration   1: 3.591 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.763 ms/op
                 createUser·p0.50:   3.494 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  12.030 ms/op
                 createUser·p0.9999: 19.895 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   2: 3.562 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  11.862 ms/op
                 createUser·p0.9999: 21.791 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   3: 3.730 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.641 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   5.857 ms/op
                 createUser·p0.999:  12.584 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 264908
  mean =      3.626 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8328 
    [ 2.500,  5.000) = 245860 
    [ 5.000,  7.500) = 9710 
    [ 7.500, 10.000) = 562 
    [10.000, 12.500) = 214 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 58 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      5.997 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     25.123 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


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
# Warmup Iteration   1: 4.414 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.536 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.008 ms/op
Iteration   1: 3.457 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.934 ms/op
                 existUser·p0.50:   3.375 ms/op
                 existUser·p0.90:   4.227 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  8.930 ms/op
                 existUser·p0.9999: 17.441 ms/op
                 existUser·p1.00:   18.055 ms/op

Iteration   2: 3.328 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   4.112 ms/op
                 existUser·p0.95:   4.432 ms/op
                 existUser·p0.99:   5.366 ms/op
                 existUser·p0.999:  7.677 ms/op
                 existUser·p0.9999: 16.822 ms/op
                 existUser·p1.00:   17.105 ms/op

Iteration   3: 3.163 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.645 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.178 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  9.549 ms/op
                 existUser·p0.9999: 23.396 ms/op
                 existUser·p1.00:   26.182 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 289799
  mean =      3.312 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19749 
    [ 2.500,  5.000) = 265622 
    [ 5.000,  7.500) = 3787 
    [ 7.500, 10.000) = 458 
    [10.000, 12.500) = 28 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.645 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.325 ms/op
     p(99.9000) =      8.720 ms/op
     p(99.9900) =     22.677 ms/op
     p(99.9990) =     25.530 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.163 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.724 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.010 ms/op
Iteration   1: 3.551 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.843 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  8.699 ms/op
                 getUser·p0.9999: 14.746 ms/op
                 getUser·p1.00:   14.926 ms/op

Iteration   2: 3.634 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  10.632 ms/op
                 getUser·p0.9999: 17.662 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   3: 3.512 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.825 ms/op
                 getUser·p0.999:  8.132 ms/op
                 getUser·p0.9999: 18.126 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 269319
  mean =      3.565 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 9591 
    [ 2.500,  3.750) = 170003 
    [ 3.750,  5.000) = 80081 
    [ 5.000,  6.250) = 7116 
    [ 6.250,  7.500) = 1538 
    [ 7.500,  8.750) = 514 
    [ 8.750, 10.000) = 121 
    [10.000, 11.250) = 67 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.731 ms/op
     p(50.0000) =      3.490 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =      9.165 ms/op
     p(99.9900) =     17.273 ms/op
     p(99.9990) =     19.222 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.428 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.857 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.681 ±(99.9%) 0.014 ms/op
Iteration   1: 4.622 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.436 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   6.070 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  15.395 ms/op
                 listUser·p0.9999: 18.648 ms/op
                 listUser·p1.00:   20.120 ms/op

Iteration   2: 4.658 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.096 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.750 ms/op
                 listUser·p0.99:   8.405 ms/op
                 listUser·p0.999:  16.037 ms/op
                 listUser·p0.9999: 27.076 ms/op
                 listUser·p1.00:   28.180 ms/op

Iteration   3: 4.668 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.039 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   6.054 ms/op
                 listUser·p0.95:   6.709 ms/op
                 listUser·p0.99:   8.438 ms/op
                 listUser·p0.999:  19.561 ms/op
                 listUser·p0.9999: 23.074 ms/op
                 listUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 206396
  mean =      4.649 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 815 
    [ 2.500,  5.000) = 152980 
    [ 5.000,  7.500) = 47617 
    [ 7.500, 10.000) = 4132 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      4.432 ms/op
     p(90.0000) =      6.021 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =      8.454 ms/op
     p(99.9000) =     17.203 ms/op
     p(99.9900) =     23.080 ms/op
     p(99.9990) =     28.137 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.972 ± 3.555  ops/ms
ClientGrpc.existUser                       thrpt       3   9.798 ± 1.870  ops/ms
ClientGrpc.getUser                         thrpt       3   9.191 ± 1.821  ops/ms
ClientGrpc.listUser                        thrpt       3   6.819 ± 0.760  ops/ms
ClientGrpc.createUser                       avgt       3   3.488 ± 0.574   ms/op
ClientGrpc.existUser                        avgt       3   3.346 ± 0.803   ms/op
ClientGrpc.getUser                          avgt       3   3.638 ± 0.685   ms/op
ClientGrpc.listUser                         avgt       3   4.695 ± 1.096   ms/op
ClientGrpc.createUser                     sample  264908   3.626 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.717           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.997           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.862           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.117           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.592           ms/op
ClientGrpc.existUser                      sample  289799   3.312 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.645           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.260           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.088           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.399           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.720           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.677           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.182           ms/op
ClientGrpc.getUser                        sample  269319   3.565 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.731           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.490           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.383           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.776           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.078           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.165           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.273           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.333           ms/op
ClientGrpc.listUser                       sample  206396   4.649 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.039           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.432           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.021           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.203           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.080           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.180           ms/op
