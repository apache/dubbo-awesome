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
# Warmup Iteration   1: 2.041 ops/ms
# Warmup Iteration   2: 4.850 ops/ms
# Warmup Iteration   3: 6.674 ops/ms
Iteration   1: 6.876 ops/ms
Iteration   2: 6.910 ops/ms
Iteration   3: 7.037 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.941 ±(99.9%) 1.547 ops/ms [Average]
  (min, avg, max) = (6.876, 6.941, 7.037), stdev = 0.085
  CI (99.9%): [5.394, 8.488] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.409 ops/ms
# Warmup Iteration   2: 6.738 ops/ms
# Warmup Iteration   3: 7.162 ops/ms
Iteration   1: 7.215 ops/ms
Iteration   2: 7.149 ops/ms
Iteration   3: 7.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.223 ±(99.9%) 1.438 ops/ms [Average]
  (min, avg, max) = (7.149, 7.223, 7.306), stdev = 0.079
  CI (99.9%): [5.786, 8.661] (assumes normal distribution)


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
# Warmup Iteration   1: 4.123 ops/ms
# Warmup Iteration   2: 6.292 ops/ms
# Warmup Iteration   3: 6.691 ops/ms
Iteration   1: 6.882 ops/ms
Iteration   2: 6.779 ops/ms
Iteration   3: 6.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.860 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (6.779, 6.860, 6.919), stdev = 0.072
  CI (99.9%): [5.539, 8.182] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.380 ops/ms
# Warmup Iteration   2: 4.637 ops/ms
# Warmup Iteration   3: 5.256 ops/ms
Iteration   1: 5.336 ops/ms
Iteration   2: 5.147 ops/ms
Iteration   3: 5.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.336 ±(99.9%) 3.451 ops/ms [Average]
  (min, avg, max) = (5.147, 5.336, 5.526), stdev = 0.189
  CI (99.9%): [1.885, 8.787] (assumes normal distribution)


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
# Warmup Iteration   1: 7.398 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.979 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.825 ±(99.9%) 0.004 ms/op
Iteration   1: 4.753 ±(99.9%) 0.002 ms/op
Iteration   2: 4.694 ±(99.9%) 0.002 ms/op
Iteration   3: 4.825 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.757 ±(99.9%) 1.193 ms/op [Average]
  (min, avg, max) = (4.694, 4.757, 4.825), stdev = 0.065
  CI (99.9%): [3.564, 5.951] (assumes normal distribution)


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
# Warmup Iteration   1: 6.551 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.765 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.422 ±(99.9%) 0.004 ms/op
Iteration   1: 4.395 ±(99.9%) 0.004 ms/op
Iteration   2: 4.478 ±(99.9%) 0.003 ms/op
Iteration   3: 4.385 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.419 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (4.385, 4.419, 4.478), stdev = 0.051
  CI (99.9%): [3.494, 5.345] (assumes normal distribution)


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
# Warmup Iteration   1: 6.707 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 5.083 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.673 ±(99.9%) 0.020 ms/op
Iteration   1: 4.686 ±(99.9%) 0.003 ms/op
Iteration   2: 4.547 ±(99.9%) 0.003 ms/op
Iteration   3: 4.489 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.574 ±(99.9%) 1.847 ms/op [Average]
  (min, avg, max) = (4.489, 4.574, 4.686), stdev = 0.101
  CI (99.9%): [2.727, 6.421] (assumes normal distribution)


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
# Warmup Iteration   1: 8.854 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.681 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 6.106 ±(99.9%) 0.014 ms/op
Iteration   1: 6.114 ±(99.9%) 0.033 ms/op
Iteration   2: 5.844 ±(99.9%) 0.024 ms/op
Iteration   3: 6.176 ±(99.9%) 0.029 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.045 ±(99.9%) 3.217 ms/op [Average]
  (min, avg, max) = (5.844, 6.045, 6.176), stdev = 0.176
  CI (99.9%): [2.828, 9.261] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.257 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.953 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.712 ±(99.9%) 0.014 ms/op
Iteration   1: 4.508 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   4.497 ms/op
                 createUser·p0.90:   5.718 ms/op
                 createUser·p0.95:   6.185 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  12.423 ms/op
                 createUser·p0.9999: 20.870 ms/op
                 createUser·p1.00:   21.561 ms/op

Iteration   2: 4.615 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.161 ms/op
                 createUser·p0.50:   4.514 ms/op
                 createUser·p0.90:   5.538 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   7.873 ms/op
                 createUser·p0.999:  16.281 ms/op
                 createUser·p0.9999: 20.255 ms/op
                 createUser·p1.00:   20.840 ms/op

Iteration   3: 4.623 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   5.652 ms/op
                 createUser·p0.95:   6.111 ms/op
                 createUser·p0.99:   7.242 ms/op
                 createUser·p0.999:  12.684 ms/op
                 createUser·p0.9999: 29.235 ms/op
                 createUser·p1.00:   29.688 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 209363
  mean =      4.581 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6339 
    [ 2.500,  5.000) = 147231 
    [ 5.000,  7.500) = 53824 
    [ 7.500, 10.000) = 1303 
    [10.000, 12.500) = 386 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.119 ms/op
     p(99.0000) =      7.430 ms/op
     p(99.9000) =     13.999 ms/op
     p(99.9900) =     28.093 ms/op
     p(99.9990) =     29.616 ms/op
     p(99.9999) =     29.688 ms/op
    p(100.0000) =     29.688 ms/op


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
# Warmup Iteration   1: 6.145 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.719 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.010 ms/op
Iteration   1: 4.405 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.850 ms/op
                 existUser·p0.50:   4.334 ms/op
                 existUser·p0.90:   5.358 ms/op
                 existUser·p0.95:   5.808 ms/op
                 existUser·p0.99:   7.261 ms/op
                 existUser·p0.999:  10.404 ms/op
                 existUser·p0.9999: 16.404 ms/op
                 existUser·p1.00:   16.941 ms/op

Iteration   2: 4.348 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.167 ms/op
                 existUser·p0.50:   4.252 ms/op
                 existUser·p0.90:   5.169 ms/op
                 existUser·p0.95:   5.603 ms/op
                 existUser·p0.99:   7.602 ms/op
                 existUser·p0.999:  14.302 ms/op
                 existUser·p0.9999: 19.015 ms/op
                 existUser·p1.00:   19.530 ms/op

Iteration   3: 4.213 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   4.211 ms/op
                 existUser·p0.90:   4.989 ms/op
                 existUser·p0.95:   5.366 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  9.649 ms/op
                 existUser·p0.9999: 20.296 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 222137
  mean =      4.320 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6551 
    [ 2.500,  5.000) = 185249 
    [ 5.000,  7.500) = 28635 
    [ 7.500, 10.000) = 1292 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.177 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     21.427 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 7.424 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.061 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.749 ±(99.9%) 0.014 ms/op
Iteration   1: 4.777 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   5.775 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   7.455 ms/op
                 getUser·p0.999:  12.505 ms/op
                 getUser·p0.9999: 22.270 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   2: 4.686 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.100 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   5.734 ms/op
                 getUser·p0.95:   6.111 ms/op
                 getUser·p0.99:   7.340 ms/op
                 getUser·p0.999:  12.183 ms/op
                 getUser·p0.9999: 19.825 ms/op
                 getUser·p1.00:   20.152 ms/op

Iteration   3: 4.695 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.043 ms/op
                 getUser·p0.50:   4.604 ms/op
                 getUser·p0.90:   5.685 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   7.373 ms/op
                 getUser·p0.999:  12.197 ms/op
                 getUser·p0.9999: 22.006 ms/op
                 getUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 203217
  mean =      4.719 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1929 
    [ 2.500,  5.000) = 135555 
    [ 5.000,  7.500) = 63872 
    [ 7.500, 10.000) = 1342 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.734 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      7.388 ms/op
     p(99.9000) =     12.252 ms/op
     p(99.9900) =     21.901 ms/op
     p(99.9990) =     22.643 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 9.422 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 6.502 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 6.071 ±(99.9%) 0.022 ms/op
Iteration   1: 5.841 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   7.922 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   10.919 ms/op
                 listUser·p0.999:  16.982 ms/op
                 listUser·p0.9999: 25.386 ms/op
                 listUser·p1.00:   25.723 ms/op

Iteration   2: 6.007 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.698 ms/op
                 listUser·p0.50:   5.702 ms/op
                 listUser·p0.90:   7.774 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.289 ms/op
                 listUser·p0.999:  20.389 ms/op
                 listUser·p0.9999: 33.151 ms/op
                 listUser·p1.00:   34.210 ms/op

Iteration   3: 6.083 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.829 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   9.093 ms/op
                 listUser·p0.99:   11.239 ms/op
                 listUser·p0.999:  19.249 ms/op
                 listUser·p0.9999: 22.774 ms/op
                 listUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 160573
  mean =      5.975 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 130 
    [ 2.500,  5.000) = 37831 
    [ 5.000,  7.500) = 102137 
    [ 7.500, 10.000) = 16917 
    [10.000, 12.500) = 2815 
    [12.500, 15.000) = 417 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      5.685 ms/op
     p(90.0000) =      7.889 ms/op
     p(95.0000) =      8.946 ms/op
     p(99.0000) =     11.141 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     32.440 ms/op
     p(99.9990) =     34.011 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.941 ± 1.547  ops/ms
ClientGrpc.existUser                       thrpt       3   7.223 ± 1.438  ops/ms
ClientGrpc.getUser                         thrpt       3   6.860 ± 1.322  ops/ms
ClientGrpc.listUser                        thrpt       3   5.336 ± 3.451  ops/ms
ClientGrpc.createUser                       avgt       3   4.757 ± 1.193   ms/op
ClientGrpc.existUser                        avgt       3   4.419 ± 0.925   ms/op
ClientGrpc.getUser                          avgt       3   4.574 ± 1.847   ms/op
ClientGrpc.listUser                         avgt       3   6.045 ± 3.217   ms/op
ClientGrpc.createUser                     sample  209363   4.581 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.114           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.522           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.636           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.119           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.430           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.999           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.093           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.688           ms/op
ClientGrpc.existUser                      sample  222137   4.320 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.850           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.177           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.612           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.127           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.025           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.104           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.692           ms/op
ClientGrpc.getUser                        sample  203217   4.719 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.043           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.734           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.095           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.388           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.252           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.901           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.708           ms/op
ClientGrpc.listUser                       sample  160573   5.975 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.370           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.685           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.889           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.946           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.141           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.431           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.440           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.210           ms/op
