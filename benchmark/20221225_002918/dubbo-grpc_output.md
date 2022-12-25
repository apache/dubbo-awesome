# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.576 ops/ms
# Warmup Iteration   2: 9.588 ops/ms
# Warmup Iteration   3: 10.476 ops/ms
Iteration   1: 10.532 ops/ms
Iteration   2: 10.913 ops/ms
Iteration   3: 10.664 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.703 ±(99.9%) 3.537 ops/ms [Average]
  (min, avg, max) = (10.532, 10.703, 10.913), stdev = 0.194
  CI (99.9%): [7.167, 14.240] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.114 ops/ms
# Warmup Iteration   2: 10.725 ops/ms
# Warmup Iteration   3: 11.202 ops/ms
Iteration   1: 11.323 ops/ms
Iteration   2: 11.768 ops/ms
Iteration   3: 11.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.380 ±(99.9%) 6.624 ops/ms [Average]
  (min, avg, max) = (11.048, 11.380, 11.768), stdev = 0.363
  CI (99.9%): [4.756, 18.004] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.351 ops/ms
# Warmup Iteration   2: 10.393 ops/ms
# Warmup Iteration   3: 10.482 ops/ms
Iteration   1: 10.818 ops/ms
Iteration   2: 10.738 ops/ms
Iteration   3: 10.740 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.765 ±(99.9%) 0.828 ops/ms [Average]
  (min, avg, max) = (10.738, 10.765, 10.818), stdev = 0.045
  CI (99.9%): [9.937, 11.594] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.645 ops/ms
# Warmup Iteration   2: 7.806 ops/ms
# Warmup Iteration   3: 7.993 ops/ms
Iteration   1: 7.838 ops/ms
Iteration   2: 8.001 ops/ms
Iteration   3: 8.163 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.001 ±(99.9%) 2.964 ops/ms [Average]
  (min, avg, max) = (7.838, 8.001, 8.163), stdev = 0.162
  CI (99.9%): [5.037, 10.965] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.827 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.004 ±(99.9%) 0.003 ms/op
Iteration   1: 2.953 ±(99.9%) 0.003 ms/op
Iteration   2: 3.097 ±(99.9%) 0.001 ms/op
Iteration   3: 3.170 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.073 ±(99.9%) 2.009 ms/op [Average]
  (min, avg, max) = (2.953, 3.073, 3.170), stdev = 0.110
  CI (99.9%): [1.064, 5.082] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.003 ms/op
Iteration   1: 2.844 ±(99.9%) 0.002 ms/op
Iteration   2: 2.922 ±(99.9%) 0.002 ms/op
Iteration   3: 2.920 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.896 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (2.844, 2.896, 2.922), stdev = 0.044
  CI (99.9%): [2.088, 3.703] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.968 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.031 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.002 ms/op
Iteration   1: 2.990 ±(99.9%) 0.002 ms/op
Iteration   2: 2.949 ±(99.9%) 0.002 ms/op
Iteration   3: 2.977 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.972 ±(99.9%) 0.384 ms/op [Average]
  (min, avg, max) = (2.949, 2.972, 2.990), stdev = 0.021
  CI (99.9%): [2.588, 3.356] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 3.717 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.984 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.007 ms/op
Iteration   1: 3.973 ±(99.9%) 0.015 ms/op
Iteration   2: 3.837 ±(99.9%) 0.039 ms/op
Iteration   3: 3.994 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.935 ±(99.9%) 1.558 ms/op [Average]
  (min, avg, max) = (3.837, 3.935, 3.994), stdev = 0.085
  CI (99.9%): [2.377, 5.492] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.983 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.989 ±(99.9%) 0.007 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.414 ms/op
                 createUser·p0.50:   2.953 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   3.965 ms/op
                 createUser·p0.999:  7.102 ms/op
                 createUser·p0.9999: 19.504 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   2: 3.045 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.891 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  9.273 ms/op
                 createUser·p0.9999: 22.348 ms/op
                 createUser·p1.00:   23.396 ms/op

Iteration   3: 2.998 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.565 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.699 ms/op
                 createUser·p0.99:   4.055 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 21.856 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319541
  mean =      3.003 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33440 
    [ 2.500,  5.000) = 285160 
    [ 5.000,  7.500) = 562 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.414 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.129 ms/op
     p(99.9000) =      8.255 ms/op
     p(99.9900) =     21.856 ms/op
     p(99.9990) =     23.331 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.611 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 2.860 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.736 ±(99.9%) 0.006 ms/op
Iteration   1: 2.802 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   2.847 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.404 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  6.314 ms/op
                 existUser·p0.9999: 12.750 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 2.811 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.626 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  6.021 ms/op
                 existUser·p0.9999: 13.673 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   3: 2.821 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.558 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.334 ms/op
                 existUser·p0.999:  6.178 ms/op
                 existUser·p0.9999: 16.378 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 341337
  mean =      2.811 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5376 
    [ 1.250,  2.500) = 66203 
    [ 2.500,  3.750) = 258758 
    [ 3.750,  5.000) = 10295 
    [ 5.000,  6.250) = 381 
    [ 6.250,  7.500) = 132 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.346 ms/op
     p(95.0000) =      3.580 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.158 ms/op
     p(99.9900) =     14.615 ms/op
     p(99.9990) =     16.816 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.806 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.006 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  5.652 ms/op
                 getUser·p0.9999: 16.895 ms/op
                 getUser·p1.00:   17.138 ms/op

Iteration   2: 2.911 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.643 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.437 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  8.426 ms/op
                 getUser·p0.9999: 21.332 ms/op
                 getUser·p1.00:   21.823 ms/op

Iteration   3: 3.002 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.456 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  7.037 ms/op
                 getUser·p0.9999: 15.134 ms/op
                 getUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 320361
  mean =      2.996 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37572 
    [ 2.500,  5.000) = 281996 
    [ 5.000,  7.500) = 556 
    [ 7.500, 10.000) = 77 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.456 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      6.849 ms/op
     p(99.9900) =     20.264 ms/op
     p(99.9990) =     21.712 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.127 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.940 ±(99.9%) 0.011 ms/op
Iteration   1: 3.940 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.188 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  12.250 ms/op
                 listUser·p0.9999: 14.090 ms/op
                 listUser·p1.00:   16.368 ms/op

Iteration   2: 3.928 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  18.079 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 3.908 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.466 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.676 ms/op
                 listUser·p0.9999: 26.797 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244805
  mean =      3.925 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4805 
    [ 2.500,  5.000) = 216463 
    [ 5.000,  7.500) = 22326 
    [ 7.500, 10.000) = 696 
    [10.000, 12.500) = 157 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.466 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     15.017 ms/op
     p(99.9900) =     25.417 ms/op
     p(99.9990) =     27.052 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.703 ± 3.537  ops/ms
ClientGrpc.existUser                       thrpt       3  11.380 ± 6.624  ops/ms
ClientGrpc.getUser                         thrpt       3  10.765 ± 0.828  ops/ms
ClientGrpc.listUser                        thrpt       3   8.001 ± 2.964  ops/ms
ClientGrpc.createUser                       avgt       3   3.073 ± 2.009   ms/op
ClientGrpc.existUser                        avgt       3   2.896 ± 0.807   ms/op
ClientGrpc.getUser                          avgt       3   2.972 ± 0.384   ms/op
ClientGrpc.listUser                         avgt       3   3.935 ± 1.558   ms/op
ClientGrpc.createUser                     sample  319541   3.003 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.414           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.564           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.129           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.255           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.856           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.396           ms/op
ClientGrpc.existUser                      sample  341337   2.811 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.558           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.346           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.158           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.615           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.974           ms/op
ClientGrpc.getUser                        sample  320361   2.996 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.456           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.137           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.849           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.264           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.823           ms/op
ClientGrpc.listUser                       sample  244805   3.925 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.466           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.973           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.017           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.417           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.132           ms/op
