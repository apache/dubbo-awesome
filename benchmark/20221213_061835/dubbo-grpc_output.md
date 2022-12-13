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
# Warmup Iteration   1: 3.286 ops/ms
# Warmup Iteration   2: 7.136 ops/ms
# Warmup Iteration   3: 8.324 ops/ms
Iteration   1: 8.270 ops/ms
Iteration   2: 8.213 ops/ms
Iteration   3: 8.406 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.296 ±(99.9%) 1.814 ops/ms [Average]
  (min, avg, max) = (8.213, 8.296, 8.406), stdev = 0.099
  CI (99.9%): [6.482, 10.111] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.221 ops/ms
# Warmup Iteration   2: 8.601 ops/ms
# Warmup Iteration   3: 8.926 ops/ms
Iteration   1: 9.348 ops/ms
Iteration   2: 9.356 ops/ms
Iteration   3: 9.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.309 ±(99.9%) 1.369 ops/ms [Average]
  (min, avg, max) = (9.222, 9.309, 9.356), stdev = 0.075
  CI (99.9%): [7.939, 10.678] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.612 ops/ms
# Warmup Iteration   2: 8.624 ops/ms
# Warmup Iteration   3: 8.794 ops/ms
Iteration   1: 8.987 ops/ms
Iteration   2: 9.041 ops/ms
Iteration   3: 9.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.028 ±(99.9%) 0.659 ops/ms [Average]
  (min, avg, max) = (8.987, 9.028, 9.056), stdev = 0.036
  CI (99.9%): [8.369, 9.687] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.811 ops/ms
# Warmup Iteration   2: 6.349 ops/ms
# Warmup Iteration   3: 7.190 ops/ms
Iteration   1: 7.369 ops/ms
Iteration   2: 7.485 ops/ms
Iteration   3: 7.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.302 ±(99.9%) 4.081 ops/ms [Average]
  (min, avg, max) = (7.053, 7.302, 7.485), stdev = 0.224
  CI (99.9%): [3.221, 11.384] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.467 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.682 ±(99.9%) 0.003 ms/op
Iteration   1: 3.531 ±(99.9%) 0.014 ms/op
Iteration   2: 3.652 ±(99.9%) 0.003 ms/op
Iteration   3: 3.491 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.558 ±(99.9%) 1.523 ms/op [Average]
  (min, avg, max) = (3.491, 3.558, 3.652), stdev = 0.084
  CI (99.9%): [2.035, 5.081] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.630 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.002 ms/op
Iteration   1: 3.523 ±(99.9%) 0.004 ms/op
Iteration   2: 3.521 ±(99.9%) 0.003 ms/op
Iteration   3: 3.296 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.446 ±(99.9%) 2.380 ms/op [Average]
  (min, avg, max) = (3.296, 3.446, 3.523), stdev = 0.130
  CI (99.9%): [1.066, 5.826] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.824 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.003 ms/op
Iteration   1: 3.619 ±(99.9%) 0.004 ms/op
Iteration   2: 3.676 ±(99.9%) 0.004 ms/op
Iteration   3: 3.717 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.671 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (3.619, 3.671, 3.717), stdev = 0.049
  CI (99.9%): [2.777, 4.565] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.049 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 5.039 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.690 ±(99.9%) 0.019 ms/op
Iteration   1: 4.649 ±(99.9%) 0.004 ms/op
Iteration   2: 4.628 ±(99.9%) 0.006 ms/op
Iteration   3: 4.753 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.677 ±(99.9%) 1.221 ms/op [Average]
  (min, avg, max) = (4.628, 4.677, 4.753), stdev = 0.067
  CI (99.9%): [3.456, 5.898] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.550 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.862 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.009 ms/op
Iteration   1: 3.729 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.356 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.784 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  14.533 ms/op
                 createUser·p0.9999: 21.964 ms/op
                 createUser·p1.00:   22.512 ms/op

Iteration   2: 3.713 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   5.235 ms/op
                 createUser·p0.999:  8.471 ms/op
                 createUser·p0.9999: 23.343 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   3: 3.652 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  12.789 ms/op
                 createUser·p0.9999: 20.790 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 259596
  mean =      3.698 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3302 
    [ 2.500,  5.000) = 250732 
    [ 5.000,  7.500) = 4823 
    [ 7.500, 10.000) = 296 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     12.698 ms/op
     p(99.9900) =     22.417 ms/op
     p(99.9990) =     23.698 ms/op
     p(99.9999) =     23.822 ms/op
    p(100.0000) =     23.822 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.049 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.739 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.626 ±(99.9%) 0.008 ms/op
Iteration   1: 3.534 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.995 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.366 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   4.997 ms/op
                 existUser·p0.999:  7.147 ms/op
                 existUser·p0.9999: 15.023 ms/op
                 existUser·p1.00:   15.368 ms/op

Iteration   2: 3.633 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.864 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.637 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  7.731 ms/op
                 existUser·p0.9999: 19.123 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   3: 3.509 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.541 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   4.907 ms/op
                 existUser·p0.999:  8.077 ms/op
                 existUser·p0.9999: 19.591 ms/op
                 existUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269856
  mean =      3.558 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14481 
    [ 2.500,  5.000) = 252719 
    [ 5.000,  7.500) = 2332 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      4.997 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     20.385 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 5.168 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.790 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.708 ±(99.9%) 0.009 ms/op
Iteration   1: 3.678 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   5.243 ms/op
                 getUser·p0.999:  10.210 ms/op
                 getUser·p0.9999: 20.248 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 3.618 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.010 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.147 ms/op
                 getUser·p0.999:  9.033 ms/op
                 getUser·p0.9999: 18.556 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   3: 3.667 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.456 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.169 ms/op
                 getUser·p0.999:  9.418 ms/op
                 getUser·p0.9999: 23.003 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 262698
  mean =      3.654 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6255 
    [ 2.500,  5.000) = 252188 
    [ 5.000,  7.500) = 3824 
    [ 7.500, 10.000) = 202 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      5.186 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     22.256 ms/op
     p(99.9990) =     23.245 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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
# Warmup Iteration   1: 6.745 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.007 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.796 ±(99.9%) 0.014 ms/op
Iteration   1: 4.547 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   5.582 ms/op
                 listUser·p0.95:   6.242 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  14.169 ms/op
                 listUser·p0.9999: 18.543 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   2: 4.578 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.743 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.578 ms/op
                 listUser·p0.99:   7.832 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 20.447 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   3: 4.520 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   4.342 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.267 ms/op
                 listUser·p0.99:   7.823 ms/op
                 listUser·p0.999:  19.524 ms/op
                 listUser·p0.9999: 22.872 ms/op
                 listUser·p1.00:   23.396 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 211012
  mean =      4.548 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 874 
    [ 2.500,  5.000) = 169549 
    [ 5.000,  7.500) = 37429 
    [ 7.500, 10.000) = 2544 
    [10.000, 12.500) = 235 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.926 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.734 ms/op
     p(95.0000) =      6.368 ms/op
     p(99.0000) =      7.856 ms/op
     p(99.9000) =     17.563 ms/op
     p(99.9900) =     21.525 ms/op
     p(99.9990) =     23.196 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.296 ± 1.814  ops/ms
ClientGrpc.existUser                       thrpt       3   9.309 ± 1.369  ops/ms
ClientGrpc.getUser                         thrpt       3   9.028 ± 0.659  ops/ms
ClientGrpc.listUser                        thrpt       3   7.302 ± 4.081  ops/ms
ClientGrpc.createUser                       avgt       3   3.558 ± 1.523   ms/op
ClientGrpc.existUser                        avgt       3   3.446 ± 2.380   ms/op
ClientGrpc.getUser                          avgt       3   3.671 ± 0.894   ms/op
ClientGrpc.listUser                         avgt       3   4.677 ± 1.221   ms/op
ClientGrpc.createUser                     sample  259596   3.698 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.356           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.637           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.382           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.698           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.417           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.822           ms/op
ClientGrpc.existUser                      sample  269856   3.558 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.541           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.997           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.815           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.038           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.775           ms/op
ClientGrpc.getUser                        sample  262698   3.654 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.903           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.186           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.355           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.256           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  211012   4.548 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.926           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.375           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.368           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.856           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.563           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.525           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.396           ms/op
