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
# Warmup Iteration   1: 3.261 ops/ms
# Warmup Iteration   2: 7.359 ops/ms
# Warmup Iteration   3: 8.093 ops/ms
Iteration   1: 8.719 ops/ms
Iteration   2: 8.946 ops/ms
Iteration   3: 8.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.858 ±(99.9%) 2.234 ops/ms [Average]
  (min, avg, max) = (8.719, 8.858, 8.946), stdev = 0.122
  CI (99.9%): [6.625, 11.092] (assumes normal distribution)


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
# Warmup Iteration   1: 6.190 ops/ms
# Warmup Iteration   2: 8.644 ops/ms
# Warmup Iteration   3: 8.890 ops/ms
Iteration   1: 9.254 ops/ms
Iteration   2: 9.314 ops/ms
Iteration   3: 9.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.442 ±(99.9%) 5.024 ops/ms [Average]
  (min, avg, max) = (9.254, 9.442, 9.758), stdev = 0.275
  CI (99.9%): [4.418, 14.466] (assumes normal distribution)


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
# Warmup Iteration   1: 5.628 ops/ms
# Warmup Iteration   2: 8.395 ops/ms
# Warmup Iteration   3: 8.880 ops/ms
Iteration   1: 9.023 ops/ms
Iteration   2: 9.024 ops/ms
Iteration   3: 8.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.004 ±(99.9%) 0.619 ops/ms [Average]
  (min, avg, max) = (8.965, 9.004, 9.024), stdev = 0.034
  CI (99.9%): [8.384, 9.623] (assumes normal distribution)


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
# Warmup Iteration   1: 4.404 ops/ms
# Warmup Iteration   2: 6.070 ops/ms
# Warmup Iteration   3: 6.598 ops/ms
Iteration   1: 6.817 ops/ms
Iteration   2: 6.828 ops/ms
Iteration   3: 6.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.795 ±(99.9%) 0.897 ops/ms [Average]
  (min, avg, max) = (6.738, 6.795, 6.828), stdev = 0.049
  CI (99.9%): [5.897, 7.692] (assumes normal distribution)


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
# Warmup Iteration   1: 5.563 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.763 ±(99.9%) 0.015 ms/op
Iteration   1: 3.518 ±(99.9%) 0.004 ms/op
Iteration   2: 3.555 ±(99.9%) 0.003 ms/op
Iteration   3: 3.677 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.583 ±(99.9%) 1.518 ms/op [Average]
  (min, avg, max) = (3.518, 3.583, 3.677), stdev = 0.083
  CI (99.9%): [2.065, 5.102] (assumes normal distribution)


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
# Warmup Iteration   1: 5.459 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.519 ±(99.9%) 0.004 ms/op
Iteration   1: 3.418 ±(99.9%) 0.002 ms/op
Iteration   2: 3.420 ±(99.9%) 0.002 ms/op
Iteration   3: 3.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.444 ±(99.9%) 0.787 ms/op [Average]
  (min, avg, max) = (3.418, 3.444, 3.494), stdev = 0.043
  CI (99.9%): [2.657, 4.231] (assumes normal distribution)


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
# Warmup Iteration   1: 5.525 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.839 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.635 ±(99.9%) 0.003 ms/op
Iteration   1: 3.619 ±(99.9%) 0.005 ms/op
Iteration   2: 3.645 ±(99.9%) 0.007 ms/op
Iteration   3: 3.630 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.631 ±(99.9%) 0.245 ms/op [Average]
  (min, avg, max) = (3.619, 3.631, 3.645), stdev = 0.013
  CI (99.9%): [3.386, 3.877] (assumes normal distribution)


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
# Warmup Iteration   1: 6.757 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.888 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.712 ±(99.9%) 0.017 ms/op
Iteration   1: 4.683 ±(99.9%) 0.009 ms/op
Iteration   2: 4.591 ±(99.9%) 0.009 ms/op
Iteration   3: 4.718 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.664 ±(99.9%) 1.192 ms/op [Average]
  (min, avg, max) = (4.591, 4.664, 4.718), stdev = 0.065
  CI (99.9%): [3.472, 5.856] (assumes normal distribution)


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
# Warmup Iteration   1: 5.339 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.725 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.009 ms/op
Iteration   1: 3.582 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.061 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.174 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   6.028 ms/op
                 createUser·p0.999:  14.706 ms/op
                 createUser·p0.9999: 31.588 ms/op
                 createUser·p1.00:   33.227 ms/op

Iteration   2: 3.591 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  11.039 ms/op
                 createUser·p0.9999: 20.644 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 3.551 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.787 ms/op
                 createUser·p0.50:   3.486 ms/op
                 createUser·p0.90:   4.129 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.702 ms/op
                 createUser·p0.999:  16.838 ms/op
                 createUser·p0.9999: 23.282 ms/op
                 createUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 268672
  mean =      3.575 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7552 
    [ 2.500,  5.000) = 254427 
    [ 5.000,  7.500) = 5725 
    [ 7.500, 10.000) = 634 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.787 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     14.003 ms/op
     p(99.9900) =     31.237 ms/op
     p(99.9990) =     33.008 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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
# Warmup Iteration   1: 4.855 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.709 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.508 ±(99.9%) 0.008 ms/op
Iteration   1: 3.512 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   3.461 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  8.660 ms/op
                 existUser·p0.9999: 19.591 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   2: 3.406 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.834 ms/op
                 existUser·p0.50:   3.371 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  11.503 ms/op
                 existUser·p0.9999: 34.381 ms/op
                 existUser·p1.00:   34.734 ms/op

Iteration   3: 3.412 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  9.350 ms/op
                 existUser·p0.9999: 22.500 ms/op
                 existUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 278759
  mean =      3.443 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10276 
    [ 2.500,  5.000) = 263653 
    [ 5.000,  7.500) = 4047 
    [ 7.500, 10.000) = 472 
    [10.000, 12.500) = 150 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.533 ms/op
     p(99.9000) =     10.510 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     34.617 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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
# Warmup Iteration   1: 5.196 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.009 ms/op
Iteration   1: 3.683 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.600 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   6.267 ms/op
                 getUser·p0.999:  13.860 ms/op
                 getUser·p0.9999: 22.882 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.604 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  10.895 ms/op
                 getUser·p0.9999: 35.594 ms/op
                 getUser·p1.00:   37.028 ms/op

Iteration   3: 3.618 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.141 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   5.439 ms/op
                 getUser·p0.999:  8.633 ms/op
                 getUser·p0.9999: 23.986 ms/op
                 getUser·p1.00:   24.052 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 264145
  mean =      3.634 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5995 
    [ 2.500,  5.000) = 251502 
    [ 5.000,  7.500) = 5660 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 18 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     10.977 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     36.962 ms/op
     p(99.9999) =     37.028 ms/op
    p(100.0000) =     37.028 ms/op


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
# Warmup Iteration   1: 6.606 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.149 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.842 ±(99.9%) 0.016 ms/op
Iteration   1: 4.708 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.442 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.930 ms/op
                 listUser·p0.95:   6.717 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  18.579 ms/op
                 listUser·p0.9999: 20.880 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   2: 4.672 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.440 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.661 ms/op
                 listUser·p0.95:   6.431 ms/op
                 listUser·p0.99:   8.126 ms/op
                 listUser·p0.999:  20.382 ms/op
                 listUser·p0.9999: 25.738 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   3: 4.741 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.545 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  19.708 ms/op
                 listUser·p0.9999: 23.462 ms/op
                 listUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 203907
  mean =      4.707 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 374 
    [ 2.500,  5.000) = 158345 
    [ 5.000,  7.500) = 40888 
    [ 7.500, 10.000) = 3573 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 160 
    [20.000, 22.500) = 102 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.139 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.816 ms/op
     p(95.0000) =      6.578 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     19.241 ms/op
     p(99.9900) =     23.928 ms/op
     p(99.9990) =     26.205 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.858 ± 2.234  ops/ms
ClientGrpc.existUser                       thrpt       3   9.442 ± 5.024  ops/ms
ClientGrpc.getUser                         thrpt       3   9.004 ± 0.619  ops/ms
ClientGrpc.listUser                        thrpt       3   6.795 ± 0.897  ops/ms
ClientGrpc.createUser                       avgt       3   3.583 ± 1.518   ms/op
ClientGrpc.existUser                        avgt       3   3.444 ± 0.787   ms/op
ClientGrpc.getUser                          avgt       3   3.631 ± 0.245   ms/op
ClientGrpc.listUser                         avgt       3   4.664 ± 1.192   ms/op
ClientGrpc.createUser                     sample  268672   3.575 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.787           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.816           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.003           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.237           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.227           ms/op
ClientGrpc.existUser                      sample  278759   3.443 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.659           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.022           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.533           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.510           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.554           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.734           ms/op
ClientGrpc.getUser                        sample  264145   3.634 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.721           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.563           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.964           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.977           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.603           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          37.028           ms/op
ClientGrpc.listUser                       sample  203907   4.707 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.139           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.816           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.578           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.380           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.241           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.928           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.313           ms/op
