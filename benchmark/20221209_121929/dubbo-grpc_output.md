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
# Warmup Iteration   1: 4.478 ops/ms
# Warmup Iteration   2: 9.349 ops/ms
# Warmup Iteration   3: 10.134 ops/ms
Iteration   1: 10.756 ops/ms
Iteration   2: 10.162 ops/ms
Iteration   3: 10.255 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.391 ±(99.9%) 5.827 ops/ms [Average]
  (min, avg, max) = (10.162, 10.391, 10.756), stdev = 0.319
  CI (99.9%): [4.564, 16.218] (assumes normal distribution)


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
# Warmup Iteration   1: 7.832 ops/ms
# Warmup Iteration   2: 10.609 ops/ms
# Warmup Iteration   3: 11.129 ops/ms
Iteration   1: 10.739 ops/ms
Iteration   2: 10.744 ops/ms
Iteration   3: 10.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.797 ±(99.9%) 1.766 ops/ms [Average]
  (min, avg, max) = (10.739, 10.797, 10.909), stdev = 0.097
  CI (99.9%): [9.031, 12.564] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.540 ops/ms
# Warmup Iteration   2: 10.569 ops/ms
# Warmup Iteration   3: 10.141 ops/ms
Iteration   1: 10.614 ops/ms
Iteration   2: 10.304 ops/ms
Iteration   3: 10.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.493 ±(99.9%) 3.022 ops/ms [Average]
  (min, avg, max) = (10.304, 10.493, 10.614), stdev = 0.166
  CI (99.9%): [7.471, 13.515] (assumes normal distribution)


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
# Warmup Iteration   1: 6.101 ops/ms
# Warmup Iteration   2: 7.601 ops/ms
# Warmup Iteration   3: 7.754 ops/ms
Iteration   1: 7.830 ops/ms
Iteration   2: 8.225 ops/ms
Iteration   3: 8.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.055 ±(99.9%) 3.705 ops/ms [Average]
  (min, avg, max) = (7.830, 8.055, 8.225), stdev = 0.203
  CI (99.9%): [4.350, 11.761] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.280 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.006 ms/op
Iteration   1: 3.112 ±(99.9%) 0.002 ms/op
Iteration   2: 3.163 ±(99.9%) 0.001 ms/op
Iteration   3: 3.179 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.151 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (3.112, 3.151, 3.179), stdev = 0.035
  CI (99.9%): [2.516, 3.787] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.760 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.994 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.003 ms/op
Iteration   1: 2.967 ±(99.9%) 0.002 ms/op
Iteration   2: 2.985 ±(99.9%) 0.003 ms/op
Iteration   3: 3.003 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.985 ±(99.9%) 0.324 ms/op [Average]
  (min, avg, max) = (2.967, 2.985, 3.003), stdev = 0.018
  CI (99.9%): [2.661, 3.309] (assumes normal distribution)


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
# Warmup Iteration   1: 3.947 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.003 ms/op
Iteration   1: 3.030 ±(99.9%) 0.002 ms/op
Iteration   2: 2.979 ±(99.9%) 0.002 ms/op
Iteration   3: 3.104 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.038 ±(99.9%) 1.141 ms/op [Average]
  (min, avg, max) = (2.979, 3.038, 3.104), stdev = 0.063
  CI (99.9%): [1.897, 4.179] (assumes normal distribution)


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
# Warmup Iteration   1: 5.156 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.011 ms/op
Iteration   1: 4.075 ±(99.9%) 0.007 ms/op
Iteration   2: 4.080 ±(99.9%) 0.047 ms/op
Iteration   3: 4.076 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.077 ±(99.9%) 0.047 ms/op [Average]
  (min, avg, max) = (4.075, 4.077, 4.080), stdev = 0.003
  CI (99.9%): [4.030, 4.124] (assumes normal distribution)


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
# Warmup Iteration   1: 4.355 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.119 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.006 ms/op
Iteration   1: 3.077 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.647 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  10.800 ms/op
                 createUser·p0.9999: 13.386 ms/op
                 createUser·p1.00:   13.451 ms/op

Iteration   2: 3.196 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.308 ms/op
                 createUser·p0.9999: 13.763 ms/op
                 createUser·p1.00:   20.677 ms/op

Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.503 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  12.828 ms/op
                 createUser·p0.9999: 16.705 ms/op
                 createUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305806
  mean =      3.137 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24304 
    [ 2.500,  5.000) = 280363 
    [ 5.000,  7.500) = 613 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 156 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.503 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     10.404 ms/op
     p(99.9900) =     15.015 ms/op
     p(99.9990) =     17.070 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 3.478 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.999 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.006 ms/op
Iteration   1: 3.002 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  6.582 ms/op
                 existUser·p0.9999: 12.752 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   2: 2.946 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.375 ms/op
                 existUser·p0.9999: 20.550 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.424 ms/op
                 existUser·p0.9999: 16.717 ms/op
                 existUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321888
  mean =      2.980 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47306 
    [ 2.500,  5.000) = 273772 
    [ 5.000,  7.500) = 631 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.440 ms/op
     p(99.9900) =     19.084 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


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
# Warmup Iteration   1: 3.783 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.646 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  10.964 ms/op
                 getUser·p0.9999: 14.979 ms/op
                 getUser·p1.00:   15.401 ms/op

Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.709 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.267 ms/op
                 getUser·p0.9999: 16.989 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   3: 3.029 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.680 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.255 ms/op
                 getUser·p0.999:  6.868 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311915
  mean =      3.077 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25457 
    [ 2.500,  5.000) = 285297 
    [ 5.000,  7.500) = 854 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.646 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      7.431 ms/op
     p(99.9900) =     20.408 ms/op
     p(99.9990) =     22.475 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 4.916 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.192 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.074 ±(99.9%) 0.013 ms/op
Iteration   1: 4.060 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  13.000 ms/op
                 listUser·p0.9999: 16.040 ms/op
                 listUser·p1.00:   16.433 ms/op

Iteration   2: 3.915 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   6.663 ms/op
                 listUser·p0.999:  15.210 ms/op
                 listUser·p0.9999: 23.030 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 4.098 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.755 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   5.366 ms/op
                 listUser·p0.95:   5.825 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  14.908 ms/op
                 listUser·p0.9999: 22.190 ms/op
                 listUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238485
  mean =      4.023 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4728 
    [ 2.500,  5.000) = 202238 
    [ 5.000,  7.500) = 30272 
    [ 7.500, 10.000) = 795 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 164 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     23.273 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.391 ± 5.827  ops/ms
ClientGrpc.existUser                       thrpt       3  10.797 ± 1.766  ops/ms
ClientGrpc.getUser                         thrpt       3  10.493 ± 3.022  ops/ms
ClientGrpc.listUser                        thrpt       3   8.055 ± 3.705  ops/ms
ClientGrpc.createUser                       avgt       3   3.151 ± 0.635   ms/op
ClientGrpc.existUser                        avgt       3   2.985 ± 0.324   ms/op
ClientGrpc.getUser                          avgt       3   3.038 ± 1.141   ms/op
ClientGrpc.listUser                         avgt       3   4.077 ± 0.047   ms/op
ClientGrpc.createUser                     sample  305806   3.137 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.503           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.404           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.015           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.677           ms/op
ClientGrpc.existUser                      sample  321888   2.980 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.633           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.440           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.084           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.299           ms/op
ClientGrpc.getUser                        sample  311915   3.077 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.646           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.064           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.871           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.431           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.408           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  238485   4.023 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.755           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.336           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.315           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.396           ms/op
