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
# Warmup Iteration   1: 2.985 ops/ms
# Warmup Iteration   2: 7.290 ops/ms
# Warmup Iteration   3: 8.244 ops/ms
Iteration   1: 8.904 ops/ms
Iteration   2: 9.331 ops/ms
Iteration   3: 9.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.179 ±(99.9%) 4.349 ops/ms [Average]
  (min, avg, max) = (8.904, 9.179, 9.331), stdev = 0.238
  CI (99.9%): [4.830, 13.528] (assumes normal distribution)


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
# Warmup Iteration   1: 6.906 ops/ms
# Warmup Iteration   2: 8.825 ops/ms
# Warmup Iteration   3: 9.508 ops/ms
Iteration   1: 9.634 ops/ms
Iteration   2: 9.728 ops/ms
Iteration   3: 9.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.667 ±(99.9%) 0.965 ops/ms [Average]
  (min, avg, max) = (9.634, 9.667, 9.728), stdev = 0.053
  CI (99.9%): [8.703, 10.632] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.674 ops/ms
# Warmup Iteration   2: 8.204 ops/ms
# Warmup Iteration   3: 9.246 ops/ms
Iteration   1: 9.034 ops/ms
Iteration   2: 9.342 ops/ms
Iteration   3: 9.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.148 ±(99.9%) 3.071 ops/ms [Average]
  (min, avg, max) = (9.034, 9.148, 9.342), stdev = 0.168
  CI (99.9%): [6.078, 12.219] (assumes normal distribution)


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
# Warmup Iteration   1: 4.631 ops/ms
# Warmup Iteration   2: 6.555 ops/ms
# Warmup Iteration   3: 6.924 ops/ms
Iteration   1: 7.027 ops/ms
Iteration   2: 7.083 ops/ms
Iteration   3: 7.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.047 ±(99.9%) 0.569 ops/ms [Average]
  (min, avg, max) = (7.027, 7.047, 7.083), stdev = 0.031
  CI (99.9%): [6.478, 7.616] (assumes normal distribution)


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
# Warmup Iteration   1: 5.194 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.615 ±(99.9%) 0.014 ms/op
Iteration   1: 3.605 ±(99.9%) 0.003 ms/op
Iteration   2: 3.470 ±(99.9%) 0.003 ms/op
Iteration   3: 3.509 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.528 ±(99.9%) 1.269 ms/op [Average]
  (min, avg, max) = (3.470, 3.528, 3.605), stdev = 0.070
  CI (99.9%): [2.259, 4.796] (assumes normal distribution)


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
# Warmup Iteration   1: 4.627 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.003 ms/op
Iteration   1: 3.425 ±(99.9%) 0.003 ms/op
Iteration   2: 3.408 ±(99.9%) 0.002 ms/op
Iteration   3: 3.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.430 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (3.408, 3.430, 3.457), stdev = 0.025
  CI (99.9%): [2.974, 3.886] (assumes normal distribution)


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
# Warmup Iteration   1: 4.813 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.529 ±(99.9%) 0.002 ms/op
Iteration   1: 3.479 ±(99.9%) 0.005 ms/op
Iteration   2: 3.565 ±(99.9%) 0.004 ms/op
Iteration   3: 3.534 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.526 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (3.479, 3.526, 3.565), stdev = 0.044
  CI (99.9%): [2.732, 4.320] (assumes normal distribution)


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
# Warmup Iteration   1: 6.503 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.925 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.618 ±(99.9%) 0.026 ms/op
Iteration   1: 4.635 ±(99.9%) 0.020 ms/op
Iteration   2: 4.585 ±(99.9%) 0.015 ms/op
Iteration   3: 4.592 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.604 ±(99.9%) 0.488 ms/op [Average]
  (min, avg, max) = (4.585, 4.604, 4.635), stdev = 0.027
  CI (99.9%): [4.115, 5.092] (assumes normal distribution)


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.008 ms/op
Iteration   1: 3.458 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.855 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   5.136 ms/op
                 createUser·p0.999:  8.319 ms/op
                 createUser·p0.9999: 23.323 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.369 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  9.994 ms/op
                 createUser·p0.9999: 16.384 ms/op
                 createUser·p1.00:   16.810 ms/op

Iteration   3: 3.501 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.745 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  15.869 ms/op
                 createUser·p0.9999: 24.473 ms/op
                 createUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 278908
  mean =      3.442 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13910 
    [ 2.500,  5.000) = 260927 
    [ 5.000,  7.500) = 3436 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     10.094 ms/op
     p(99.9900) =     23.433 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


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
# Warmup Iteration   1: 4.325 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.472 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.006 ms/op
Iteration   1: 3.396 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.965 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.724 ms/op
                 existUser·p0.9999: 14.470 ms/op
                 existUser·p1.00:   14.811 ms/op

Iteration   2: 3.328 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.965 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.830 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  9.843 ms/op
                 existUser·p0.9999: 15.979 ms/op
                 existUser·p1.00:   16.171 ms/op

Iteration   3: 3.388 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   3.342 ms/op
                 existUser·p0.90:   3.916 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  12.036 ms/op
                 existUser·p0.9999: 21.055 ms/op
                 existUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 284762
  mean =      3.371 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9068 
    [ 2.500,  5.000) = 271814 
    [ 5.000,  7.500) = 3381 
    [ 7.500, 10.000) = 233 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.284 ms/op
     p(99.9000) =      9.830 ms/op
     p(99.9900) =     20.464 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 5.066 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.517 ±(99.9%) 0.008 ms/op
Iteration   1: 3.525 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  11.412 ms/op
                 getUser·p0.9999: 15.956 ms/op
                 getUser·p1.00:   16.318 ms/op

Iteration   2: 3.440 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  7.618 ms/op
                 getUser·p0.9999: 30.366 ms/op
                 getUser·p1.00:   30.638 ms/op

Iteration   3: 3.467 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.776 ms/op
                 getUser·p0.50:   3.428 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.334 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  10.863 ms/op
                 getUser·p0.9999: 19.711 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 276141
  mean =      3.477 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13975 
    [ 2.500,  5.000) = 256336 
    [ 5.000,  7.500) = 5327 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.776 ms/op
     p(50.0000) =      3.441 ms/op
     p(90.0000) =      4.141 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =     10.762 ms/op
     p(99.9900) =     29.156 ms/op
     p(99.9990) =     30.507 ms/op
     p(99.9999) =     30.638 ms/op
    p(100.0000) =     30.638 ms/op


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
# Warmup Iteration   1: 6.786 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 4.919 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.713 ±(99.9%) 0.014 ms/op
Iteration   1: 4.633 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.923 ms/op
                 listUser·p0.95:   6.775 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 20.096 ms/op
                 listUser·p1.00:   22.282 ms/op

Iteration   2: 4.651 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   6.005 ms/op
                 listUser·p0.95:   6.676 ms/op
                 listUser·p0.99:   8.487 ms/op
                 listUser·p0.999:  17.007 ms/op
                 listUser·p0.9999: 28.115 ms/op
                 listUser·p1.00:   29.360 ms/op

Iteration   3: 4.590 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.685 ms/op
                 listUser·p0.95:   6.545 ms/op
                 listUser·p0.99:   8.282 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 24.674 ms/op
                 listUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207455
  mean =      4.625 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 581 
    [ 2.500,  5.000) = 163129 
    [ 5.000,  7.500) = 39008 
    [ 7.500, 10.000) = 4118 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.882 ms/op
     p(95.0000) =      6.668 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     27.697 ms/op
     p(99.9990) =     29.322 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.179 ± 4.349  ops/ms
ClientGrpc.existUser                       thrpt       3   9.667 ± 0.965  ops/ms
ClientGrpc.getUser                         thrpt       3   9.148 ± 3.071  ops/ms
ClientGrpc.listUser                        thrpt       3   7.047 ± 0.569  ops/ms
ClientGrpc.createUser                       avgt       3   3.528 ± 1.269   ms/op
ClientGrpc.existUser                        avgt       3   3.430 ± 0.456   ms/op
ClientGrpc.getUser                          avgt       3   3.526 ± 0.794   ms/op
ClientGrpc.listUser                         avgt       3   4.604 ± 0.488   ms/op
ClientGrpc.createUser                     sample  278908   3.442 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.745           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.424           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.071           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.317           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.094           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.433           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.674           ms/op
ClientGrpc.existUser                      sample  284762   3.371 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.628           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.903           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.830           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.464           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.168           ms/op
ClientGrpc.getUser                        sample  276141   3.477 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.776           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.441           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.141           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.762           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.156           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.638           ms/op
ClientGrpc.listUser                       sample  207455   4.625 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.049           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.407           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.348           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.974           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.697           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.360           ms/op
