# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.995 ops/ms
# Warmup Iteration   2: 4.878 ops/ms
# Warmup Iteration   3: 6.817 ops/ms
Iteration   1: 6.773 ops/ms
Iteration   2: 7.143 ops/ms
Iteration   3: 7.094 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.003 ±(99.9%) 3.666 ops/ms [Average]
  (min, avg, max) = (6.773, 7.003, 7.143), stdev = 0.201
  CI (99.9%): [3.337, 10.670] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.583 ops/ms
# Warmup Iteration   2: 6.882 ops/ms
# Warmup Iteration   3: 7.386 ops/ms
Iteration   1: 7.677 ops/ms
Iteration   2: 7.409 ops/ms
Iteration   3: 7.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.562 ±(99.9%) 2.519 ops/ms [Average]
  (min, avg, max) = (7.409, 7.562, 7.677), stdev = 0.138
  CI (99.9%): [5.043, 10.082] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 4.527 ops/ms
# Warmup Iteration   2: 6.410 ops/ms
# Warmup Iteration   3: 6.938 ops/ms
Iteration   1: 7.092 ops/ms
Iteration   2: 7.233 ops/ms
Iteration   3: 7.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.109 ±(99.9%) 2.116 ops/ms [Average]
  (min, avg, max) = (7.003, 7.109, 7.233), stdev = 0.116
  CI (99.9%): [4.993, 9.226] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.457 ops/ms
# Warmup Iteration   2: 4.842 ops/ms
# Warmup Iteration   3: 5.266 ops/ms
Iteration   1: 5.304 ops/ms
Iteration   2: 5.218 ops/ms
Iteration   3: 5.303 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.275 ±(99.9%) 0.904 ops/ms [Average]
  (min, avg, max) = (5.218, 5.275, 5.304), stdev = 0.050
  CI (99.9%): [4.371, 6.179] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.727 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.222 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.878 ±(99.9%) 0.004 ms/op
Iteration   1: 4.610 ±(99.9%) 0.005 ms/op
Iteration   2: 4.792 ±(99.9%) 0.005 ms/op
Iteration   3: 4.740 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.714 ±(99.9%) 1.711 ms/op [Average]
  (min, avg, max) = (4.610, 4.714, 4.792), stdev = 0.094
  CI (99.9%): [3.002, 6.425] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.404 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.666 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.428 ±(99.9%) 0.007 ms/op
Iteration   1: 4.386 ±(99.9%) 0.003 ms/op
Iteration   2: 4.275 ±(99.9%) 0.004 ms/op
Iteration   3: 4.214 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.291 ±(99.9%) 1.588 ms/op [Average]
  (min, avg, max) = (4.214, 4.291, 4.386), stdev = 0.087
  CI (99.9%): [2.704, 5.879] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 6.936 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.831 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.588 ±(99.9%) 0.007 ms/op
Iteration   1: 4.598 ±(99.9%) 0.004 ms/op
Iteration   2: 4.508 ±(99.9%) 0.006 ms/op
Iteration   3: 4.622 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.576 ±(99.9%) 1.103 ms/op [Average]
  (min, avg, max) = (4.508, 4.576, 4.622), stdev = 0.060
  CI (99.9%): [3.473, 5.679] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.100 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 6.196 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 6.161 ±(99.9%) 0.019 ms/op
Iteration   1: 6.093 ±(99.9%) 0.034 ms/op
Iteration   2: 6.244 ±(99.9%) 0.019 ms/op
Iteration   3: 5.854 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.064 ±(99.9%) 3.582 ms/op [Average]
  (min, avg, max) = (5.854, 6.064, 6.244), stdev = 0.196
  CI (99.9%): [2.481, 9.646] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.760 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 4.923 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.592 ±(99.9%) 0.015 ms/op
Iteration   1: 4.452 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.636 ms/op
                 createUser·p0.95:   6.201 ms/op
                 createUser·p0.99:   8.520 ms/op
                 createUser·p0.999:  11.914 ms/op
                 createUser·p0.9999: 19.708 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 4.395 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.579 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   8.200 ms/op
                 createUser·p0.999:  12.939 ms/op
                 createUser·p0.9999: 17.452 ms/op
                 createUser·p1.00:   18.317 ms/op

Iteration   3: 4.461 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.782 ms/op
                 createUser·p0.50:   4.317 ms/op
                 createUser·p0.90:   5.521 ms/op
                 createUser·p0.95:   6.062 ms/op
                 createUser·p0.99:   8.039 ms/op
                 createUser·p0.999:  19.530 ms/op
                 createUser·p0.9999: 22.781 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 216636
  mean =      4.436 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6402 
    [ 2.500,  5.000) = 164910 
    [ 5.000,  7.500) = 41958 
    [ 7.500, 10.000) = 2649 
    [10.000, 12.500) = 466 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.782 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      8.266 ms/op
     p(99.9000) =     15.172 ms/op
     p(99.9900) =     21.572 ms/op
     p(99.9990) =     23.877 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.614 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.615 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.014 ms/op
Iteration   1: 4.339 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   4.174 ms/op
                 existUser·p0.90:   5.513 ms/op
                 existUser·p0.95:   6.038 ms/op
                 existUser·p0.99:   7.815 ms/op
                 existUser·p0.999:  11.542 ms/op
                 existUser·p0.9999: 26.071 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   2: 4.202 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   4.071 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   7.758 ms/op
                 existUser·p0.999:  13.908 ms/op
                 existUser·p0.9999: 18.244 ms/op
                 existUser·p1.00:   19.300 ms/op

Iteration   3: 4.194 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.936 ms/op
                 existUser·p0.50:   4.047 ms/op
                 existUser·p0.90:   5.251 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.784 ms/op
                 existUser·p0.999:  14.107 ms/op
                 existUser·p0.9999: 21.508 ms/op
                 existUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 226161
  mean =      4.244 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5255 
    [ 2.500,  5.000) = 186574 
    [ 5.000,  7.500) = 31634 
    [ 7.500, 10.000) = 1995 
    [10.000, 12.500) = 400 
    [12.500, 15.000) = 180 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.799 ms/op
     p(99.9000) =     13.599 ms/op
     p(99.9900) =     25.092 ms/op
     p(99.9990) =     26.370 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.742 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.944 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.542 ±(99.9%) 0.015 ms/op
Iteration   1: 4.566 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   4.415 ms/op
                 getUser·p0.90:   5.800 ms/op
                 getUser·p0.95:   6.373 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  14.336 ms/op
                 getUser·p0.9999: 24.183 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 4.548 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.710 ms/op
                 getUser·p0.95:   6.267 ms/op
                 getUser·p0.99:   8.618 ms/op
                 getUser·p0.999:  13.736 ms/op
                 getUser·p0.9999: 25.788 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   3: 4.428 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.652 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  13.042 ms/op
                 getUser·p0.9999: 34.851 ms/op
                 getUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 212553
  mean =      4.513 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6875 
    [ 2.500,  5.000) = 154509 
    [ 5.000,  7.500) = 47224 
    [ 7.500, 10.000) = 2978 
    [10.000, 12.500) = 664 
    [12.500, 15.000) = 150 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 31 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.726 ms/op
     p(95.0000) =      6.259 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     13.770 ms/op
     p(99.9900) =     34.603 ms/op
     p(99.9990) =     35.250 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.812 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 6.453 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.913 ±(99.9%) 0.026 ms/op
Iteration   1: 5.927 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.630 ms/op
                 listUser·p0.50:   5.497 ms/op
                 listUser·p0.90:   8.192 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   12.386 ms/op
                 listUser·p0.999:  18.217 ms/op
                 listUser·p0.9999: 20.899 ms/op
                 listUser·p1.00:   22.774 ms/op

Iteration   2: 5.917 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   5.472 ms/op
                 listUser·p0.90:   8.126 ms/op
                 listUser·p0.95:   9.273 ms/op
                 listUser·p0.99:   11.787 ms/op
                 listUser·p0.999:  18.248 ms/op
                 listUser·p0.9999: 24.759 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   3: 5.855 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   5.431 ms/op
                 listUser·p0.90:   8.094 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.108 ms/op
                 listUser·p0.999:  22.991 ms/op
                 listUser·p0.9999: 26.378 ms/op
                 listUser·p1.00:   27.689 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 162672
  mean =      5.900 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 169 
    [ 2.500,  5.000) = 51407 
    [ 5.000,  7.500) = 87640 
    [ 7.500, 10.000) = 18183 
    [10.000, 12.500) = 3915 
    [12.500, 15.000) = 821 
    [15.000, 17.500) = 291 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      5.464 ms/op
     p(90.0000) =      8.143 ms/op
     p(95.0000) =      9.257 ms/op
     p(99.0000) =     12.141 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     25.878 ms/op
     p(99.9990) =     27.155 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.003 ± 3.666  ops/ms
ClientGrpc.existUser                       thrpt       3   7.562 ± 2.519  ops/ms
ClientGrpc.getUser                         thrpt       3   7.109 ± 2.116  ops/ms
ClientGrpc.listUser                        thrpt       3   5.275 ± 0.904  ops/ms
ClientGrpc.createUser                       avgt       3   4.714 ± 1.711   ms/op
ClientGrpc.existUser                        avgt       3   4.291 ± 1.588   ms/op
ClientGrpc.getUser                          avgt       3   4.576 ± 1.103   ms/op
ClientGrpc.listUser                         avgt       3   6.064 ± 3.582   ms/op
ClientGrpc.createUser                     sample  216636   4.436 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.782           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.136           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.266           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.172           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.572           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.150           ms/op
ClientGrpc.existUser                      sample  226161   4.244 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.860           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.092           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.849           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.799           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.599           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.092           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.706           ms/op
ClientGrpc.getUser                        sample  212553   4.513 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.031           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.375           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.726           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.259           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.770           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          34.603           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          35.979           ms/op
ClientGrpc.listUser                       sample  162672   5.900 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.106           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.143           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.257           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.141           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.366           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.878           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.689           ms/op
