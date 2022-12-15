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
# Warmup Iteration   1: 2.334 ops/ms
# Warmup Iteration   2: 5.900 ops/ms
# Warmup Iteration   3: 7.413 ops/ms
Iteration   1: 7.697 ops/ms
Iteration   2: 7.914 ops/ms
Iteration   3: 7.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.704 ±(99.9%) 3.772 ops/ms [Average]
  (min, avg, max) = (7.501, 7.704, 7.914), stdev = 0.207
  CI (99.9%): [3.932, 11.476] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.716 ops/ms
# Warmup Iteration   2: 7.423 ops/ms
# Warmup Iteration   3: 7.726 ops/ms
Iteration   1: 7.863 ops/ms
Iteration   2: 7.546 ops/ms
Iteration   3: 8.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.851 ±(99.9%) 5.466 ops/ms [Average]
  (min, avg, max) = (7.546, 7.851, 8.145), stdev = 0.300
  CI (99.9%): [2.386, 13.317] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.381 ops/ms
# Warmup Iteration   2: 6.836 ops/ms
# Warmup Iteration   3: 7.344 ops/ms
Iteration   1: 7.287 ops/ms
Iteration   2: 7.698 ops/ms
Iteration   3: 7.042 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.342 ±(99.9%) 6.048 ops/ms [Average]
  (min, avg, max) = (7.042, 7.342, 7.698), stdev = 0.332
  CI (99.9%): [1.294, 13.391] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.956 ops/ms
# Warmup Iteration   2: 5.256 ops/ms
# Warmup Iteration   3: 5.560 ops/ms
Iteration   1: 5.563 ops/ms
Iteration   2: 5.683 ops/ms
Iteration   3: 5.576 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.607 ±(99.9%) 1.204 ops/ms [Average]
  (min, avg, max) = (5.563, 5.607, 5.683), stdev = 0.066
  CI (99.9%): [4.403, 6.811] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.965 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.527 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.563 ±(99.9%) 0.004 ms/op
Iteration   1: 4.392 ±(99.9%) 0.003 ms/op
Iteration   2: 4.428 ±(99.9%) 0.005 ms/op
Iteration   3: 4.327 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.382 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (4.327, 4.382, 4.428), stdev = 0.051
  CI (99.9%): [3.446, 5.319] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.346 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.354 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.006 ms/op
Iteration   1: 4.085 ±(99.9%) 0.003 ms/op
Iteration   2: 3.965 ±(99.9%) 0.003 ms/op
Iteration   3: 3.989 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.013 ±(99.9%) 1.165 ms/op [Average]
  (min, avg, max) = (3.965, 4.013, 4.085), stdev = 0.064
  CI (99.9%): [2.848, 5.178] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.114 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.616 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.338 ±(99.9%) 0.005 ms/op
Iteration   1: 4.272 ±(99.9%) 0.003 ms/op
Iteration   2: 4.212 ±(99.9%) 0.004 ms/op
Iteration   3: 4.215 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.233 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (4.212, 4.233, 4.272), stdev = 0.034
  CI (99.9%): [3.617, 4.850] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 9.347 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.876 ±(99.9%) 0.053 ms/op
# Warmup Iteration   3: 5.787 ±(99.9%) 0.016 ms/op
Iteration   1: 5.838 ±(99.9%) 0.024 ms/op
Iteration   2: 5.922 ±(99.9%) 0.016 ms/op
Iteration   3: 5.684 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.815 ±(99.9%) 2.198 ms/op [Average]
  (min, avg, max) = (5.684, 5.815, 5.922), stdev = 0.120
  CI (99.9%): [3.617, 8.012] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.364 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 4.698 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.343 ±(99.9%) 0.015 ms/op
Iteration   1: 4.314 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   4.157 ms/op
                 createUser·p0.90:   5.505 ms/op
                 createUser·p0.95:   6.062 ms/op
                 createUser·p0.99:   7.995 ms/op
                 createUser·p0.999:  12.544 ms/op
                 createUser·p0.9999: 20.721 ms/op
                 createUser·p1.00:   21.266 ms/op

Iteration   2: 4.382 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.849 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.554 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   7.989 ms/op
                 createUser·p0.999:  13.222 ms/op
                 createUser·p0.9999: 35.397 ms/op
                 createUser·p1.00:   36.372 ms/op

Iteration   3: 4.352 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.620 ms/op
                 createUser·p0.95:   6.177 ms/op
                 createUser·p0.99:   8.738 ms/op
                 createUser·p0.999:  21.054 ms/op
                 createUser·p0.9999: 27.393 ms/op
                 createUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 220562
  mean =      4.349 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4541 
    [ 2.500,  5.000) = 170675 
    [ 5.000,  7.500) = 41933 
    [ 7.500, 10.000) = 2520 
    [10.000, 12.500) = 519 
    [12.500, 15.000) = 175 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.562 ms/op
     p(95.0000) =      6.126 ms/op
     p(99.0000) =      8.143 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     34.075 ms/op
     p(99.9990) =     36.095 ms/op
     p(99.9999) =     36.372 ms/op
    p(100.0000) =     36.372 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.926 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.555 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.216 ±(99.9%) 0.014 ms/op
Iteration   1: 4.314 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   4.145 ms/op
                 existUser·p0.90:   5.554 ms/op
                 existUser·p0.95:   6.201 ms/op
                 existUser·p0.99:   8.487 ms/op
                 existUser·p0.999:  12.727 ms/op
                 existUser·p0.9999: 17.536 ms/op
                 existUser·p1.00:   18.022 ms/op

Iteration   2: 4.016 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.915 ms/op
                 existUser·p0.50:   3.965 ms/op
                 existUser·p0.90:   5.218 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   7.624 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 18.713 ms/op
                 existUser·p1.00:   19.825 ms/op

Iteration   3: 4.124 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.159 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   5.202 ms/op
                 existUser·p0.95:   5.677 ms/op
                 existUser·p0.99:   7.381 ms/op
                 existUser·p0.999:  10.902 ms/op
                 existUser·p0.9999: 24.068 ms/op
                 existUser·p1.00:   26.575 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231443
  mean =      4.148 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9520 
    [ 2.500,  5.000) = 185489 
    [ 5.000,  7.500) = 33428 
    [ 7.500, 10.000) = 2358 
    [10.000, 12.500) = 463 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     11.773 ms/op
     p(99.9900) =     23.593 ms/op
     p(99.9990) =     25.260 ms/op
     p(99.9999) =     26.575 ms/op
    p(100.0000) =     26.575 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.715 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.737 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.295 ±(99.9%) 0.014 ms/op
Iteration   1: 4.276 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   4.125 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   5.882 ms/op
                 getUser·p0.99:   7.684 ms/op
                 getUser·p0.999:  15.205 ms/op
                 getUser·p0.9999: 18.777 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   2: 4.372 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   6.054 ms/op
                 getUser·p0.99:   9.093 ms/op
                 getUser·p0.999:  14.010 ms/op
                 getUser·p0.9999: 19.433 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   3: 4.262 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   4.092 ms/op
                 getUser·p0.90:   5.308 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   7.922 ms/op
                 getUser·p0.999:  14.324 ms/op
                 getUser·p0.9999: 22.249 ms/op
                 getUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 223064
  mean =      4.303 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3557 
    [ 2.500,  5.000) = 183735 
    [ 5.000,  7.500) = 32623 
    [ 7.500, 10.000) = 2208 
    [10.000, 12.500) = 545 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      4.133 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.947 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     14.662 ms/op
     p(99.9900) =     21.312 ms/op
     p(99.9990) =     24.069 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.475 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.645 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.878 ±(99.9%) 0.026 ms/op
Iteration   1: 5.970 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.446 ms/op
                 listUser·p0.50:   5.480 ms/op
                 listUser·p0.90:   8.389 ms/op
                 listUser·p0.95:   9.535 ms/op
                 listUser·p0.99:   12.911 ms/op
                 listUser·p0.999:  20.326 ms/op
                 listUser·p0.9999: 27.153 ms/op
                 listUser·p1.00:   28.082 ms/op

Iteration   2: 5.603 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.561 ms/op
                 listUser·p0.50:   5.267 ms/op
                 listUser·p0.90:   7.627 ms/op
                 listUser·p0.95:   8.503 ms/op
                 listUser·p0.99:   10.404 ms/op
                 listUser·p0.999:  17.452 ms/op
                 listUser·p0.9999: 21.810 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   3: 5.561 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   5.226 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.364 ms/op
                 listUser·p0.99:   10.535 ms/op
                 listUser·p0.999:  24.751 ms/op
                 listUser·p0.9999: 29.884 ms/op
                 listUser·p1.00:   31.490 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168316
  mean =      5.705 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 143 
    [ 2.500,  5.000) = 63967 
    [ 5.000,  7.500) = 82870 
    [ 7.500, 10.000) = 17705 
    [10.000, 12.500) = 2564 
    [12.500, 15.000) = 522 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 35 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      5.308 ms/op
     p(90.0000) =      7.856 ms/op
     p(95.0000) =      8.782 ms/op
     p(99.0000) =     11.420 ms/op
     p(99.9000) =     21.223 ms/op
     p(99.9900) =     29.721 ms/op
     p(99.9990) =     30.416 ms/op
     p(99.9999) =     31.490 ms/op
    p(100.0000) =     31.490 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.704 ± 3.772  ops/ms
ClientGrpc.existUser                       thrpt       3   7.851 ± 5.466  ops/ms
ClientGrpc.getUser                         thrpt       3   7.342 ± 6.048  ops/ms
ClientGrpc.listUser                        thrpt       3   5.607 ± 1.204  ops/ms
ClientGrpc.createUser                       avgt       3   4.382 ± 0.937   ms/op
ClientGrpc.existUser                        avgt       3   4.013 ± 1.165   ms/op
ClientGrpc.getUser                          avgt       3   4.233 ± 0.616   ms/op
ClientGrpc.listUser                         avgt       3   5.815 ± 2.198   ms/op
ClientGrpc.createUser                     sample  220562   4.349 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.849           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.194           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.126           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.143           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.631           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.075           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          36.372           ms/op
ClientGrpc.existUser                      sample  231443   4.148 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.915           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.026           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.325           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.849           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.873           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.773           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.593           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.575           ms/op
ClientGrpc.getUser                        sample  223064   4.303 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.970           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.133           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.366           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.947           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.135           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.662           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.312           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.510           ms/op
ClientGrpc.listUser                       sample  168316   5.705 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.446           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.856           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.782           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.420           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.223           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.721           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.490           ms/op
