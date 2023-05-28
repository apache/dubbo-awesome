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
# Warmup Iteration   1: 2.737 ops/ms
# Warmup Iteration   2: 6.552 ops/ms
# Warmup Iteration   3: 7.623 ops/ms
Iteration   1: 8.247 ops/ms
Iteration   2: 7.711 ops/ms
Iteration   3: 8.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.021 ±(99.9%) 5.072 ops/ms [Average]
  (min, avg, max) = (7.711, 8.021, 8.247), stdev = 0.278
  CI (99.9%): [2.949, 13.093] (assumes normal distribution)


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
# Warmup Iteration   1: 5.638 ops/ms
# Warmup Iteration   2: 8.128 ops/ms
# Warmup Iteration   3: 9.015 ops/ms
Iteration   1: 9.119 ops/ms
Iteration   2: 9.249 ops/ms
Iteration   3: 9.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.219 ±(99.9%) 1.624 ops/ms [Average]
  (min, avg, max) = (9.119, 9.219, 9.289), stdev = 0.089
  CI (99.9%): [7.595, 10.842] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 5.140 ops/ms
# Warmup Iteration   2: 7.750 ops/ms
# Warmup Iteration   3: 8.112 ops/ms
Iteration   1: 8.057 ops/ms
Iteration   2: 7.809 ops/ms
Iteration   3: 8.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.034 ±(99.9%) 3.900 ops/ms [Average]
  (min, avg, max) = (7.809, 8.034, 8.235), stdev = 0.214
  CI (99.9%): [4.133, 11.934] (assumes normal distribution)


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
# Warmup Iteration   1: 4.471 ops/ms
# Warmup Iteration   2: 5.907 ops/ms
# Warmup Iteration   3: 6.408 ops/ms
Iteration   1: 6.704 ops/ms
Iteration   2: 6.202 ops/ms
Iteration   3: 6.728 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.545 ±(99.9%) 5.418 ops/ms [Average]
  (min, avg, max) = (6.202, 6.545, 6.728), stdev = 0.297
  CI (99.9%): [1.127, 11.963] (assumes normal distribution)


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
# Warmup Iteration   1: 5.679 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.132 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.003 ms/op
Iteration   1: 3.810 ±(99.9%) 0.002 ms/op
Iteration   2: 3.740 ±(99.9%) 0.003 ms/op
Iteration   3: 3.691 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.747 ±(99.9%) 1.092 ms/op [Average]
  (min, avg, max) = (3.691, 3.747, 3.810), stdev = 0.060
  CI (99.9%): [2.655, 4.839] (assumes normal distribution)


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
# Warmup Iteration   1: 4.946 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.876 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.005 ms/op
Iteration   1: 3.392 ±(99.9%) 0.003 ms/op
Iteration   2: 3.641 ±(99.9%) 0.004 ms/op
Iteration   3: 3.635 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.556 ±(99.9%) 2.593 ms/op [Average]
  (min, avg, max) = (3.392, 3.556, 3.641), stdev = 0.142
  CI (99.9%): [0.963, 6.149] (assumes normal distribution)


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
# Warmup Iteration   1: 5.973 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.443 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.004 ms/op
Iteration   1: 3.703 ±(99.9%) 0.002 ms/op
Iteration   2: 3.733 ±(99.9%) 0.004 ms/op
Iteration   3: 3.733 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.723 ±(99.9%) 0.317 ms/op [Average]
  (min, avg, max) = (3.703, 3.723, 3.733), stdev = 0.017
  CI (99.9%): [3.406, 4.039] (assumes normal distribution)


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
# Warmup Iteration   1: 7.154 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 5.337 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.056 ±(99.9%) 0.018 ms/op
Iteration   1: 4.742 ±(99.9%) 0.022 ms/op
Iteration   2: 4.788 ±(99.9%) 0.019 ms/op
Iteration   3: 4.648 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.726 ±(99.9%) 1.303 ms/op [Average]
  (min, avg, max) = (4.648, 4.726, 4.788), stdev = 0.071
  CI (99.9%): [3.423, 6.029] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.260 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.011 ms/op
Iteration   1: 3.710 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.916 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.087 ms/op
                 createUser·p0.99:   6.267 ms/op
                 createUser·p0.999:  10.073 ms/op
                 createUser·p0.9999: 20.230 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   2: 3.680 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.909 ms/op
                 createUser·p0.50:   3.576 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.841 ms/op
                 createUser·p0.99:   6.210 ms/op
                 createUser·p0.999:  13.849 ms/op
                 createUser·p0.9999: 20.664 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 3.677 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.863 ms/op
                 createUser·p0.50:   3.588 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  9.515 ms/op
                 createUser·p0.9999: 19.506 ms/op
                 createUser·p1.00:   19.890 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260288
  mean =      3.689 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6358 
    [ 2.500,  5.000) = 241394 
    [ 5.000,  7.500) = 11513 
    [ 7.500, 10.000) = 709 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 103 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.029 ms/op
     p(99.9000) =     10.710 ms/op
     p(99.9900) =     20.251 ms/op
     p(99.9990) =     21.285 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 5.262 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.554 ±(99.9%) 0.009 ms/op
Iteration   1: 3.667 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.416 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   4.989 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  9.858 ms/op
                 existUser·p0.9999: 15.742 ms/op
                 existUser·p1.00:   17.367 ms/op

Iteration   2: 3.633 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.375 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  7.905 ms/op
                 existUser·p0.9999: 17.433 ms/op
                 existUser·p1.00:   17.924 ms/op

Iteration   3: 3.542 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.796 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   4.465 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  9.133 ms/op
                 existUser·p0.9999: 16.285 ms/op
                 existUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 265693
  mean =      3.613 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 226 
    [ 1.250,  2.500) = 10476 
    [ 2.500,  3.750) = 157499 
    [ 3.750,  5.000) = 87335 
    [ 5.000,  6.250) = 8078 
    [ 6.250,  7.500) = 1289 
    [ 7.500,  8.750) = 435 
    [ 8.750, 10.000) = 145 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 56 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.416 ms/op
     p(50.0000) =      3.539 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     17.727 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 5.365 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.821 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.631 ±(99.9%) 0.010 ms/op
Iteration   1: 3.577 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.506 ms/op
                 getUser·p0.90:   4.506 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  8.939 ms/op
                 getUser·p0.9999: 20.353 ms/op
                 getUser·p1.00:   21.430 ms/op

Iteration   2: 3.627 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   3.555 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.678 ms/op
                 getUser·p0.99:   5.661 ms/op
                 getUser·p0.999:  11.072 ms/op
                 getUser·p0.9999: 23.074 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   3: 3.540 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.478 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  9.552 ms/op
                 getUser·p0.9999: 21.065 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267988
  mean =      3.581 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7631 
    [ 2.500,  5.000) = 252684 
    [ 5.000,  7.500) = 6887 
    [ 7.500, 10.000) = 561 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.796 ms/op
     p(50.0000) =      3.510 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     22.774 ms/op
     p(99.9990) =     23.307 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 6.879 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.137 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.051 ±(99.9%) 0.015 ms/op
Iteration   1: 4.706 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   4.506 ms/op
                 listUser·p0.90:   5.931 ms/op
                 listUser·p0.95:   6.709 ms/op
                 listUser·p0.99:   8.831 ms/op
                 listUser·p0.999:  13.357 ms/op
                 listUser·p0.9999: 18.901 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   2: 4.830 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   6.939 ms/op
                 listUser·p0.99:   9.151 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 22.524 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 4.918 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   4.710 ms/op
                 listUser·p0.90:   6.300 ms/op
                 listUser·p0.95:   7.078 ms/op
                 listUser·p0.99:   9.208 ms/op
                 listUser·p0.999:  19.993 ms/op
                 listUser·p0.9999: 22.521 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199331
  mean =      4.817 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 442 
    [ 2.500,  5.000) = 136262 
    [ 5.000,  7.500) = 56552 
    [ 7.500, 10.000) = 5053 
    [10.000, 12.500) = 633 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.305 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      6.119 ms/op
     p(95.0000) =      6.922 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     22.088 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.021 ± 5.072  ops/ms
ClientGrpc.existUser                       thrpt       3   9.219 ± 1.624  ops/ms
ClientGrpc.getUser                         thrpt       3   8.034 ± 3.900  ops/ms
ClientGrpc.listUser                        thrpt       3   6.545 ± 5.418  ops/ms
ClientGrpc.createUser                       avgt       3   3.747 ± 1.092   ms/op
ClientGrpc.existUser                        avgt       3   3.556 ± 2.593   ms/op
ClientGrpc.getUser                          avgt       3   3.723 ± 0.317   ms/op
ClientGrpc.listUser                         avgt       3   4.726 ± 1.303   ms/op
ClientGrpc.createUser                     sample  260288   3.689 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.863           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.588           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.596           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.029           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.710           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.251           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.594           ms/op
ClientGrpc.existUser                      sample  265693   3.613 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.416           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.481           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.858           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.964           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.241           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.941           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.924           ms/op
ClientGrpc.getUser                        sample  267988   3.581 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.796           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.510           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.650           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.774           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.429           ms/op
ClientGrpc.listUser                       sample  199331   4.817 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.305           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.604           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.119           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.044           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.072           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.088           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.364           ms/op
