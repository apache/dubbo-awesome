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
# Warmup Iteration   1: 2.441 ops/ms
# Warmup Iteration   2: 5.493 ops/ms
# Warmup Iteration   3: 6.813 ops/ms
Iteration   1: 7.198 ops/ms
Iteration   2: 7.273 ops/ms
Iteration   3: 7.221 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.231 ±(99.9%) 0.699 ops/ms [Average]
  (min, avg, max) = (7.198, 7.231, 7.273), stdev = 0.038
  CI (99.9%): [6.532, 7.929] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.598 ops/ms
# Warmup Iteration   2: 7.118 ops/ms
# Warmup Iteration   3: 7.515 ops/ms
Iteration   1: 7.778 ops/ms
Iteration   2: 7.960 ops/ms
Iteration   3: 7.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.830 ±(99.9%) 2.069 ops/ms [Average]
  (min, avg, max) = (7.752, 7.830, 7.960), stdev = 0.113
  CI (99.9%): [5.761, 9.899] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.208 ops/ms
# Warmup Iteration   2: 6.744 ops/ms
# Warmup Iteration   3: 7.000 ops/ms
Iteration   1: 7.293 ops/ms
Iteration   2: 7.427 ops/ms
Iteration   3: 7.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.324 ±(99.9%) 1.683 ops/ms [Average]
  (min, avg, max) = (7.250, 7.324, 7.427), stdev = 0.092
  CI (99.9%): [5.640, 9.007] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.525 ops/ms
# Warmup Iteration   2: 5.533 ops/ms
# Warmup Iteration   3: 5.822 ops/ms
Iteration   1: 5.726 ops/ms
Iteration   2: 5.809 ops/ms
Iteration   3: 5.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.772 ±(99.9%) 0.772 ops/ms [Average]
  (min, avg, max) = (5.726, 5.772, 5.809), stdev = 0.042
  CI (99.9%): [5.000, 6.543] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.434 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.593 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.515 ±(99.9%) 0.004 ms/op
Iteration   1: 4.418 ±(99.9%) 0.004 ms/op
Iteration   2: 4.335 ±(99.9%) 0.003 ms/op
Iteration   3: 4.353 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.369 ±(99.9%) 0.799 ms/op [Average]
  (min, avg, max) = (4.335, 4.369, 4.418), stdev = 0.044
  CI (99.9%): [3.570, 5.168] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.247 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.319 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.003 ms/op
Iteration   1: 4.020 ±(99.9%) 0.004 ms/op
Iteration   2: 4.149 ±(99.9%) 0.004 ms/op
Iteration   3: 4.060 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.076 ±(99.9%) 1.199 ms/op [Average]
  (min, avg, max) = (4.020, 4.076, 4.149), stdev = 0.066
  CI (99.9%): [2.877, 5.275] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.947 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.717 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.529 ±(99.9%) 0.013 ms/op
Iteration   1: 4.402 ±(99.9%) 0.004 ms/op
Iteration   2: 4.429 ±(99.9%) 0.003 ms/op
Iteration   3: 4.439 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.423 ±(99.9%) 0.348 ms/op [Average]
  (min, avg, max) = (4.402, 4.423, 4.439), stdev = 0.019
  CI (99.9%): [4.075, 4.772] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.657 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.918 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.483 ±(99.9%) 0.016 ms/op
Iteration   1: 5.453 ±(99.9%) 0.030 ms/op
Iteration   2: 5.391 ±(99.9%) 0.022 ms/op
Iteration   3: 5.382 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.409 ±(99.9%) 0.702 ms/op [Average]
  (min, avg, max) = (5.382, 5.409, 5.453), stdev = 0.039
  CI (99.9%): [4.706, 6.111] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.905 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.683 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.441 ±(99.9%) 0.013 ms/op
Iteration   1: 4.217 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.044 ms/op
                 createUser·p0.50:   4.116 ms/op
                 createUser·p0.90:   5.358 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.339 ms/op
                 createUser·p0.999:  15.397 ms/op
                 createUser·p0.9999: 18.776 ms/op
                 createUser·p1.00:   20.021 ms/op

Iteration   2: 4.344 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   4.211 ms/op
                 createUser·p0.90:   5.374 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   7.855 ms/op
                 createUser·p0.999:  11.049 ms/op
                 createUser·p0.9999: 18.270 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   3: 4.323 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   4.219 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   5.644 ms/op
                 createUser·p0.99:   6.914 ms/op
                 createUser·p0.999:  12.467 ms/op
                 createUser·p0.9999: 21.253 ms/op
                 createUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 223524
  mean =      4.294 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3605 
    [ 2.500,  5.000) = 183154 
    [ 5.000,  7.500) = 34672 
    [ 7.500, 10.000) = 1616 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.855 ms/op
     p(50.0000) =      4.186 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.395 ms/op
     p(99.9000) =     13.517 ms/op
     p(99.9900) =     20.871 ms/op
     p(99.9990) =     21.505 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.789 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.290 ±(99.9%) 0.012 ms/op
Iteration   1: 4.200 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.967 ms/op
                 existUser·p0.50:   4.100 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.595 ms/op
                 existUser·p0.99:   7.348 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 14.049 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   2: 4.026 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.128 ms/op
                 existUser·p0.50:   3.969 ms/op
                 existUser·p0.90:   5.046 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  11.151 ms/op
                 existUser·p0.9999: 21.793 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 4.017 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   3.932 ms/op
                 existUser·p0.90:   4.932 ms/op
                 existUser·p0.95:   5.317 ms/op
                 existUser·p0.99:   6.619 ms/op
                 existUser·p0.999:  10.207 ms/op
                 existUser·p0.9999: 25.562 ms/op
                 existUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 235275
  mean =      4.079 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7710 
    [ 2.500,  5.000) = 201359 
    [ 5.000,  7.500) = 24516 
    [ 7.500, 10.000) = 1297 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.994 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     24.002 ms/op
     p(99.9990) =     26.301 ms/op
     p(99.9999) =     26.345 ms/op
    p(100.0000) =     26.345 ms/op


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
# Warmup Iteration   1: 6.605 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.749 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.472 ±(99.9%) 0.012 ms/op
Iteration   1: 4.474 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   8.045 ms/op
                 getUser·p0.999:  15.835 ms/op
                 getUser·p0.9999: 21.416 ms/op
                 getUser·p1.00:   24.248 ms/op

Iteration   2: 4.463 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   4.366 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   5.849 ms/op
                 getUser·p0.99:   6.971 ms/op
                 getUser·p0.999:  10.650 ms/op
                 getUser·p0.9999: 18.334 ms/op
                 getUser·p1.00:   18.874 ms/op

Iteration   3: 4.413 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   4.317 ms/op
                 getUser·p0.90:   5.349 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   7.184 ms/op
                 getUser·p0.999:  11.748 ms/op
                 getUser·p0.9999: 21.095 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 215633
  mean =      4.450 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2068 
    [ 2.500,  5.000) = 168240 
    [ 5.000,  7.500) = 43249 
    [ 7.500, 10.000) = 1575 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.214 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.439 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     13.148 ms/op
     p(99.9900) =     20.888 ms/op
     p(99.9990) =     23.752 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 7.939 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.749 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.469 ±(99.9%) 0.018 ms/op
Iteration   1: 5.388 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   6.513 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.830 ms/op
                 listUser·p0.999:  15.967 ms/op
                 listUser·p0.9999: 18.157 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   2: 5.587 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   5.333 ms/op
                 listUser·p0.90:   7.283 ms/op
                 listUser·p0.95:   8.274 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  17.814 ms/op
                 listUser·p0.9999: 21.725 ms/op
                 listUser·p1.00:   22.118 ms/op

Iteration   3: 5.592 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.692 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.217 ms/op
                 listUser·p0.95:   8.290 ms/op
                 listUser·p0.99:   10.521 ms/op
                 listUser·p0.999:  20.441 ms/op
                 listUser·p0.9999: 26.415 ms/op
                 listUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173997
  mean =      5.520 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 79 
    [ 2.500,  5.000) = 61689 
    [ 5.000,  7.500) = 99426 
    [ 7.500, 10.000) = 10877 
    [10.000, 12.500) = 1337 
    [12.500, 15.000) = 289 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.243 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      7.012 ms/op
     p(95.0000) =      8.086 ms/op
     p(99.0000) =     10.174 ms/op
     p(99.9000) =     17.728 ms/op
     p(99.9900) =     22.525 ms/op
     p(99.9990) =     27.157 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.231 ± 0.699  ops/ms
ClientGrpc.existUser                       thrpt       3   7.830 ± 2.069  ops/ms
ClientGrpc.getUser                         thrpt       3   7.324 ± 1.683  ops/ms
ClientGrpc.listUser                        thrpt       3   5.772 ± 0.772  ops/ms
ClientGrpc.createUser                       avgt       3   4.369 ± 0.799   ms/op
ClientGrpc.existUser                        avgt       3   4.076 ± 1.199   ms/op
ClientGrpc.getUser                          avgt       3   4.423 ± 0.348   ms/op
ClientGrpc.listUser                         avgt       3   5.409 ± 0.702   ms/op
ClientGrpc.createUser                     sample  223524   4.294 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.855           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.186           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.325           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.767           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.395           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.517           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.871           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.529           ms/op
ClientGrpc.existUser                      sample  235275   4.079 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.967           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.063           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.456           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.906           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.272           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.002           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.345           ms/op
ClientGrpc.getUser                        sample  215633   4.450 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.214           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.439           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.447           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.148           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.888           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.248           ms/op
ClientGrpc.listUser                       sample  173997   5.520 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.243           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.012           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.086           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.174           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.728           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.525           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.230           ms/op
