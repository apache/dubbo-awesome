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
# Warmup Iteration   1: 2.787 ops/ms
# Warmup Iteration   2: 7.051 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 8.538 ops/ms
Iteration   2: 8.710 ops/ms
Iteration   3: 9.019 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.755 ±(99.9%) 4.442 ops/ms [Average]
  (min, avg, max) = (8.538, 8.755, 9.019), stdev = 0.243
  CI (99.9%): [4.313, 13.198] (assumes normal distribution)


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
# Warmup Iteration   1: 6.035 ops/ms
# Warmup Iteration   2: 9.207 ops/ms
# Warmup Iteration   3: 9.465 ops/ms
Iteration   1: 9.768 ops/ms
Iteration   2: 9.476 ops/ms
Iteration   3: 9.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.634 ±(99.9%) 2.686 ops/ms [Average]
  (min, avg, max) = (9.476, 9.634, 9.768), stdev = 0.147
  CI (99.9%): [6.948, 12.320] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.913 ops/ms
# Warmup Iteration   2: 7.996 ops/ms
# Warmup Iteration   3: 8.615 ops/ms
Iteration   1: 8.610 ops/ms
Iteration   2: 8.597 ops/ms
Iteration   3: 8.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.607 ±(99.9%) 0.172 ops/ms [Average]
  (min, avg, max) = (8.597, 8.607, 8.615), stdev = 0.009
  CI (99.9%): [8.435, 8.779] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 5.524 ops/ms
# Warmup Iteration   2: 6.132 ops/ms
# Warmup Iteration   3: 6.650 ops/ms
Iteration   1: 6.671 ops/ms
Iteration   2: 6.942 ops/ms
Iteration   3: 6.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.839 ±(99.9%) 2.676 ops/ms [Average]
  (min, avg, max) = (6.671, 6.839, 6.942), stdev = 0.147
  CI (99.9%): [4.163, 9.515] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.404 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.019 ms/op
Iteration   1: 3.777 ±(99.9%) 0.003 ms/op
Iteration   2: 3.553 ±(99.9%) 0.003 ms/op
Iteration   3: 3.397 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.575 ±(99.9%) 3.484 ms/op [Average]
  (min, avg, max) = (3.397, 3.575, 3.777), stdev = 0.191
  CI (99.9%): [0.091, 7.060] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.026 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.238 ±(99.9%) 0.002 ms/op
Iteration   1: 3.354 ±(99.9%) 0.002 ms/op
Iteration   2: 3.488 ±(99.9%) 0.002 ms/op
Iteration   3: 3.415 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.419 ±(99.9%) 1.230 ms/op [Average]
  (min, avg, max) = (3.354, 3.419, 3.488), stdev = 0.067
  CI (99.9%): [2.190, 4.649] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.133 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.801 ±(99.9%) 0.003 ms/op
Iteration   1: 3.816 ±(99.9%) 0.002 ms/op
Iteration   2: 3.698 ±(99.9%) 0.002 ms/op
Iteration   3: 3.725 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.746 ±(99.9%) 1.129 ms/op [Average]
  (min, avg, max) = (3.698, 3.746, 3.816), stdev = 0.062
  CI (99.9%): [2.617, 4.876] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.856 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.604 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.521 ±(99.9%) 0.014 ms/op
Iteration   1: 4.436 ±(99.9%) 0.025 ms/op
Iteration   2: 4.415 ±(99.9%) 0.010 ms/op
Iteration   3: 4.489 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.446 ±(99.9%) 0.693 ms/op [Average]
  (min, avg, max) = (4.415, 4.446, 4.489), stdev = 0.038
  CI (99.9%): [3.753, 5.139] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.337 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.795 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.649 ±(99.9%) 0.009 ms/op
Iteration   1: 3.475 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.911 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.530 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  10.615 ms/op
                 createUser·p0.9999: 18.900 ms/op
                 createUser·p1.00:   19.431 ms/op

Iteration   2: 3.516 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.767 ms/op
                 createUser·p0.50:   3.469 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.424 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  8.571 ms/op
                 createUser·p0.9999: 19.851 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   3: 3.491 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.750 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.112 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  13.794 ms/op
                 createUser·p0.9999: 22.664 ms/op
                 createUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 274671
  mean =      3.494 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10772 
    [ 2.500,  5.000) = 259828 
    [ 5.000,  7.500) = 3295 
    [ 7.500, 10.000) = 443 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.750 ms/op
     p(50.0000) =      3.449 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     10.912 ms/op
     p(99.9900) =     20.923 ms/op
     p(99.9990) =     22.774 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 4.646 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.007 ms/op
Iteration   1: 3.479 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   4.096 ms/op
                 existUser·p0.95:   4.342 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  10.843 ms/op
                 existUser·p0.9999: 15.591 ms/op
                 existUser·p1.00:   16.073 ms/op

Iteration   2: 3.467 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.485 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.162 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  12.583 ms/op
                 existUser·p0.9999: 26.167 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.355 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.801 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.940 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  10.906 ms/op
                 existUser·p0.9999: 19.492 ms/op
                 existUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 279685
  mean =      3.433 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6911 
    [ 2.500,  5.000) = 269235 
    [ 5.000,  7.500) = 2747 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.067 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =     10.912 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     26.418 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.063 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.737 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.757 ±(99.9%) 0.009 ms/op
Iteration   1: 3.744 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.891 ms/op
                 getUser·p0.50:   3.629 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  14.139 ms/op
                 getUser·p0.9999: 18.350 ms/op
                 getUser·p1.00:   18.973 ms/op

Iteration   2: 3.663 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  9.865 ms/op
                 getUser·p0.9999: 17.449 ms/op
                 getUser·p1.00:   17.924 ms/op

Iteration   3: 3.528 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.465 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.547 ms/op
                 getUser·p0.99:   5.669 ms/op
                 getUser·p0.999:  10.661 ms/op
                 getUser·p0.9999: 19.331 ms/op
                 getUser·p1.00:   20.480 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263633
  mean =      3.643 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7191 
    [ 2.500,  5.000) = 248235 
    [ 5.000,  7.500) = 7126 
    [ 7.500, 10.000) = 629 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     11.835 ms/op
     p(99.9900) =     18.136 ms/op
     p(99.9990) =     20.352 ms/op
     p(99.9999) =     20.480 ms/op
    p(100.0000) =     20.480 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.344 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.837 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.621 ±(99.9%) 0.012 ms/op
Iteration   1: 4.520 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.329 ms/op
                 listUser·p0.50:   4.375 ms/op
                 listUser·p0.90:   5.308 ms/op
                 listUser·p0.95:   6.406 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  14.980 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   2: 4.461 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.511 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.333 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  16.548 ms/op
                 listUser·p0.9999: 18.726 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   3: 4.243 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.000 ms/op
                 listUser·p0.50:   4.084 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  15.739 ms/op
                 listUser·p0.9999: 21.249 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 217917
  mean =      4.405 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 321 
    [ 2.500,  5.000) = 188976 
    [ 5.000,  7.500) = 25369 
    [ 7.500, 10.000) = 2544 
    [10.000, 12.500) = 311 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 163 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      4.260 ms/op
     p(90.0000) =      5.243 ms/op
     p(95.0000) =      6.136 ms/op
     p(99.0000) =      7.881 ms/op
     p(99.9000) =     15.910 ms/op
     p(99.9900) =     20.559 ms/op
     p(99.9990) =     21.555 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.755 ± 4.442  ops/ms
ClientGrpc.existUser                       thrpt       3   9.634 ± 2.686  ops/ms
ClientGrpc.getUser                         thrpt       3   8.607 ± 0.172  ops/ms
ClientGrpc.listUser                        thrpt       3   6.839 ± 2.676  ops/ms
ClientGrpc.createUser                       avgt       3   3.575 ± 3.484   ms/op
ClientGrpc.existUser                        avgt       3   3.419 ± 1.230   ms/op
ClientGrpc.getUser                          avgt       3   3.746 ± 1.129   ms/op
ClientGrpc.listUser                         avgt       3   4.446 ± 0.693   ms/op
ClientGrpc.createUser                     sample  274671   3.494 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.750           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.190           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.382           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.912           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.923           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.036           ms/op
ClientGrpc.existUser                      sample  279685   3.433 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.485           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.367           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.342           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.243           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.912           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.087           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.542           ms/op
ClientGrpc.getUser                        sample  263633   3.643 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.739           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.939           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.835           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.136           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.480           ms/op
ClientGrpc.listUser                       sample  217917   4.405 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.000           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.260           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.243           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.136           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.910           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.559           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.660           ms/op
